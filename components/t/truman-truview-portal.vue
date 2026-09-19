<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ewdxk1bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:truman-truview-portal" /></template>
<style>
.ewdxk1bye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.23 17.756l9.542 5.881V43.5H19.23zM41.064 6.41v8.619H10.466zM6.936 4.5h21.927L6.936 14.457z");
}

</style>
