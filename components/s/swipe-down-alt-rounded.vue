<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5ykd-b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-down-alt-rounded" /></template>
<style>
.u5ykd-b9o {
  fill: currentColor;
  d: path("M11.702 20.618q-.136-.052-.267-.183l-2.389-2.389q-.14-.14-.15-.341t.15-.366q.166-.166.357-.166t.357.166l1.74 1.74v-5.102q-1.725-.215-2.863-1.472T7.5 9.5q0-1.864 1.318-3.182T12 5t3.182 1.318T16.5 9.5q0 1.748-1.137 3.005T12.5 13.977v5.102l1.746-1.746q.14-.14.341-.15q.202-.01.367.156q.16.159.16.353t-.16.354l-2.388 2.389q-.132.13-.268.183t-.298.053t-.298-.053");
}

</style>
