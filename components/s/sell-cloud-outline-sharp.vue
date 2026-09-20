<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8i7xwxrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sell-cloud-outline-sharp" /></template>
<style>
.u8i7xwxrw {
  fill: currentColor;
  d: path("M5 21h3.302q-.152-.233-.261-.473T7.844 20H6V8.864l5.108-5.114l5.117 5.133v2.79q.275.039.527.08q.253.043.492.128V8.448L11.152 2.29L5 8.442zm6.116-12.629q-.414 0-.711-.303t-.309-.716q.012-.414.309-.717q.297-.302.71-.302q.414 0 .708.302q.294.303.312.717q-.018.413-.312.716t-.707.303M12.5 21q-1.044 0-1.772-.728T10 18.5q0-1.006.72-1.73q.719-.722 1.765-.764q.361-.9 1.18-1.453q.818-.553 1.827-.553q1.185 0 2.118.682q.934.682 1.1 1.818h.25q.875 0 1.457.678T21 18.759t-.57 1.573T19 21zm0-1h6.25q.512 0 .88-.366q.37-.367.37-.884q0-.512-.37-.88t-.88-.37h-.906l-.098-.521q-.029-.846-.698-1.413q-.67-.566-1.554-.566q-.688 0-1.274.366q-.587.365-.8 1.009l-.232.625H12.5q-.638 0-1.069.441Q11 17.883 11 18.51q0 .626.431 1.058T12.5 20m3 0");
}

</style>
