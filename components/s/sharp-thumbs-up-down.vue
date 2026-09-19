<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3g500pee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-thumbs-up-down" /></template>
<style>
.r3g500pee {
  fill: currentColor;
  d: path("M12 5H5.82l.78-3.78L5.38 0L0 5.38V14h9.24L12 7.54zm2.76 5L12 16.46V19h6.18l-.78 3.78L18.62 24L24 18.62V10z");
}

</style>
