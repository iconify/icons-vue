<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3o5dlbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-right-outline-rounded" /></template>
<style>
.a3o5dlbzz {
  fill: currentColor;
  d: path("M7.48 18.5v-7.384q0-.672.473-1.144q.472-.472 1.143-.472h8.989l-1.747-1.746q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l2.389 2.389q.242.242.242.565t-.242.566l-2.389 2.388q-.14.14-.344.15t-.363-.15t-.16-.354t.16-.354l1.746-1.746H9.096q-.269 0-.442.173t-.173.443V18.5q0 .214-.143.357T7.98 19t-.357-.143t-.143-.357");
}

</style>
