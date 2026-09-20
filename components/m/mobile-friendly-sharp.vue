<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_66zd4ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-friendly-sharp" /></template>
<style>
.i_66zd4ny {
  fill: currentColor;
  d: path("M4 23V1h14v6h-2V6H6v12h10v-1h2v6zm10.95-7l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4z");
}

</style>
