<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp73o8-du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-iphone-sharp" /></template>
<style>
.bp73o8-du {
  fill: currentColor;
  d: path("M5 23V1h14v22zm7-2.5q.425 0 .713-.288T13 19.5t-.288-.712T12 18.5t-.712.288T11 19.5t.288.713t.712.287M7 16h10V6H7z");
}

</style>
