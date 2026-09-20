<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t3gfpplgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-circle-28-filled" /></template>
<style>
.t3gfpplgd {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14S7.373 2 14 2M8.75 13.25a.75.75 0 0 0-.102 1.493l.102.007h10.5a.75.75 0 0 0 .102-1.493l-.102-.007z");
}

</style>
