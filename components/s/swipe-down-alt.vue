<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmcz43m8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-down-alt" /></template>
<style>
.nmcz43m8g {
  fill: currentColor;
  d: path("m12 22l-4-4l1.4-1.425l1.6 1.6V13.9q-1.725-.35-2.863-1.713T7 9q0-2.075 1.463-3.537T12 4t3.538 1.463T17 9q0 1.825-1.137 3.188T13 13.9v4.275l1.6-1.575L16 18z");
}

</style>
