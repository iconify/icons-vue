<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn9fb5bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outbox-alt-sharp" /></template>
<style>
.tn9fb5bmk {
  fill: currentColor;
  d: path("m6 18l12-6L6 6v4.35L11 12l-5 1.65zm-3 3V3h18v18z");
}

</style>
