<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqwq7v4mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-cafe" /></template>
<style>
.eqwq7v4mk {
  fill: currentColor;
  d: path("M20 3H4v14h14v-7h2c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 5h-2V5h2zM2 21h18v-2H2z");
}

</style>
