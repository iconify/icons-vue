<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<path class="avypvt6vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mailjet-icon" /></template>
<style>
.avypvt6vj {
  fill: var(--svg-color--9585f4, #9585f4);
  d: path("m0 97.991l93.408 42.34l18.769-18.66l-47.795-21.715l148.187-56.744l-56.961 147.533l-21.606-47.359l-18.878 18.769l.982 2.183l41.357 90.68L256 0z");
}

</style>
