<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nb-badbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paperclip-fill" /></template>
<style>
.nb-badbqm {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m37.66 50.34a8 8 0 0 0-11.32 0L87.09 143A24 24 0 1 0 121 177l49.32-50.32a8 8 0 1 1 11.42 11.2l-49.37 50.38a40 40 0 1 1-56.62-56.51L143 63.09A24 24 0 1 1 177 97l-67.29 68.6a8 8 0 1 1-11.42-11.2l67.31-68.69a8 8 0 0 0 .06-11.37");
}

</style>
