<template>
  <div>
    <nuxt />
    <footer-prismic />
  </div>
</template>

<script>
import FooterPrismic from "~/components/FooterPrismic";

export default {
  components: {
    FooterPrismic
  },
  head() {
    return {
      title: "Prismic Nuxt.js Multi Page Website"
    };
  }
};
</script>