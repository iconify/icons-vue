<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghflirbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:real-estate-agent-sharp" /></template>
<style>
.ghflirbpv {
  fill: currentColor;
  d: path("M19 15.02v-.555L8.08 10.462H7V7.289l6.5-4.635L20 7.289v7.73zm-4.904-6.578h.808v-.808h-.808zm-2 0h.808v-.808h-.808zm2 2h.808v-.808h-.808zm-2 0h.808v-.808h-.808zM2.385 21v-8.154h3V21zM14 21.808l-7.616-2.225v-6.737h2.38l7.352 2.712v1.596h-3l-2.597-.925l-.311.752l2.869.942H21V19.5z");
}

</style>
