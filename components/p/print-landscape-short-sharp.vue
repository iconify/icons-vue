<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7lcp1f2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-short-sharp" /></template>
<style>
.g7lcp1f2k {
  fill: currentColor;
  d: path("M4.77 17.98L4 17.213v-1.096H3v-1.693h1V9.321H3V7.63h1V5.752q3.023-.079 5.893-.92q2.87-.84 5.632-2.06l.667.524v11.016q-2.686 1.448-5.528 2.484q-2.843 1.037-5.895 1.185m5.529 0q1.706-.631 3.428-1.37q1.722-.738 3.428-1.659V5.764H20V17.98z");
}

</style>
