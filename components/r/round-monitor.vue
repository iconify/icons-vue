<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g45j31byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-monitor" /></template>
<style>
.g45j31byc {
  fill: currentColor;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h3c-.55.55-1 .87-1 1.59c0 .78.63 1.41 1.41 1.41h9.17c.78 0 1.41-.63 1.41-1.41c0-.72-.44-1.03-1-1.59h3c1.1 0 2-.9 2-2V5C22 3.9 21.1 3 20 3m0 13H4V5h16z");
}

</style>
