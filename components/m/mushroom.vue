<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lo-o81bvf"/><path class="huilkqbhm"/><path class="oo_zbachw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:mushroom" /></template>
<style>
.huilkqbhm {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M.05 35.216c0 9.25 14.297 16.745 31.948 16.745c17.656 0 31.952-7.495 31.952-16.745c.001-9.238-14.296-32.044-31.952-32.044C14.348 3.172.05 25.978.05 35.216");
}

.lo-o81bvf {
  fill: var(--svg-color--ddb185, #ddb185);
  d: path("M20.606 58.673c0 5.458 5.1 5.226 11.392 5.226c6.297 0 11.394.23 11.394-5.226c0-5.449-5.097-18.895-11.394-18.895c-6.293 0-11.392 13.446-11.392 18.895");
}

.oo_zbachw {
  fill: var(--svg-color--d1d2d3, #d1d2d3);
  d: path("M19.504 31.347c0 4.143-3.727 7.5-8.324 7.5s-8.327-3.358-8.327-7.5c0-4.138 3.729-7.495 8.327-7.495s8.324 3.357 8.324 7.495m38.49 5.556c0 5.525-4.981 10.015-11.114 10.015c-6.143 0-11.119-4.487-11.119-10.015c0-5.53 4.976-10.015 11.12-10.015c6.132 0 11.113 4.483 11.113 10.015M43.187 14.341c0 3.693-3.326 6.693-7.427 6.693c-4.104 0-7.427-2.999-7.427-6.693s3.323-6.686 7.427-6.686c4.1 0 7.427 2.993 7.427 6.686");
}

</style>
