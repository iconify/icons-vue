<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpfr0qgpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unfold-more-outline-rounded" /></template>
<style>
.wpfr0qgpf {
  fill: currentColor;
  d: path("m12 18.83l2.767-2.766q.147-.147.35-.156q.204-.01.37.156q.165.165.165.359t-.165.36l-2.921 2.92q-.132.132-.268.185T12 19.94t-.298-.053t-.267-.183l-2.921-2.921q-.147-.147-.156-.35q-.01-.204.156-.37q.165-.165.359-.165t.36.165zm0-13.638L9.233 7.96q-.146.146-.35.156q-.204.009-.37-.156q-.165-.166-.165-.36t.166-.36l2.92-2.92q.132-.131.268-.184q.137-.053.298-.053t.298.053t.268.183l2.92 2.922q.147.146.156.35t-.155.369q-.166.165-.36.165t-.36-.165z");
}

</style>
