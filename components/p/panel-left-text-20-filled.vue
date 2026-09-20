<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdtji4hpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-text-20-filled" /></template>
<style>
.jdtji4hpk {
  fill: currentColor;
  d: path("M15 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM9 16h6a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H9zm-4.59-2.992A.5.5 0 0 0 4.5 14h2l.09-.008A.5.5 0 0 0 6.5 13h-2zM4.5 9.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm-.09-3.492A.5.5 0 0 0 4.5 7h2l.09-.008A.5.5 0 0 0 6.5 6h-2z");
}

</style>
