<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du0aa4bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-running-with-errors" /></template>
<style>
.du0aa4bng {
  fill: currentColor;
  d: path("M22 10v8h-2v-8zm-2 10v2h2v-2zm-2-2.71A8 8 0 0 1 12 20c-4.41 0-8-3.59-8-8s3.59-8 8-8v9l7.55-7.55A9.97 9.97 0 0 0 12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c2.25 0 4.33-.74 6-2z");
}

</style>
