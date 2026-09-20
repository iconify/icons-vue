<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rqmdj4byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-12-filled" /></template>
<style>
.rqmdj4byv {
  fill: currentColor;
  d: path("M6.786 1.459a.903.903 0 0 0-1.572 0L1.122 8.628C.774 9.238 1.211 10 1.91 10h8.182c.698 0 1.135-.762.787-1.372z");
}

</style>
