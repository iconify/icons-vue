<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pqnehkd6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-opening-20-regular" /></template>
<style>
.pqnehkd6e {
  fill: currentColor;
  d: path("M12.174 11.38a8.8 8.8 0 0 1 .952-2.764c.649-1.18 1.476-2.011 2.228-2.762a.5.5 0 0 0-.708-.708l-.012.012c-.746.747-1.663 1.664-2.385 2.976C11.52 9.462 11 11.17 11 13.5a2.5 2.5 0 1 0 1.174-2.12M12 13.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0m-6.826-2.12a8.8 8.8 0 0 1 .952-2.764c.649-1.18 1.476-2.011 2.228-2.762a.5.5 0 1 0-.708-.708l-.011.012c-.747.747-1.664 1.664-2.386 2.976C4.52 9.462 4 11.17 4 13.5a2.5 2.5 0 1 0 1.174-2.12M6.5 12a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
