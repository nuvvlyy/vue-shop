<template>
  <div class="contactus">
    <Navbar></Navbar>
        <div class="container h-100">
             <div class="row p-5 h-100 justify-content-center align-items-center">
        <h1>Contact Us</h1>
      </div>
      <div class="row p-5 h-100 justify-content-center align-items-center">
        <div class="col-md-6">
          <img src="/img/svg/product.svg" alt width="400" />
        </div>
        <div class="col-md-6">
          <h3>Learn More About us</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur
            quaerat voluptate iusto? Nihil voluptas vitae veritatis magnam
            reprehenderit, reiciendis ex? Libero quasi natus veniam voluptatum,
            voluptas exercitationem ratione consectetur et!
          </p>
          <button class="btn custom-btn btn-outline-primary mr-4">Browse Products</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactUs",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>