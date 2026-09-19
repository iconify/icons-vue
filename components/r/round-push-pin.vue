<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_opmzhpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-push-pin" /></template>
<style>
.o_opmzhpl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 12.87c0-.47-.34-.85-.8-.98A3 3 0 0 1 16 9V4h1c.55 0 1-.45 1-1s-.45-1-1-1H7c-.55 0-1 .45-1 1s.45 1 1 1h1v5c0 1.38-.93 2.54-2.2 2.89c-.46.13-.8.51-.8.98V13c0 .55.45 1 1 1h4.98l.02 7c0 .55.45 1 1 1s1-.45 1-1l-.02-7H18c.55 0 1-.45 1-1z");
}

</style>
