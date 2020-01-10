<template>
  <div>
    <Header></Header>
    <TeamBody></TeamBody>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./Header.vue";
import SponsorsBody from "./TeamBody.vue";
import Footer from "./Footer.vue";

export default {
  name: "Team",
  props: {},
  components: {
    Header,
    SponsorsBody,
    Footer
  }
};
</script>