<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcyvncc0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:takeout-dining-2-sharp" /></template>
<style>
.kcyvncc0h {
  fill: currentColor;
  d: path("M3 22L7.05 5.75L7 5.05q-.025-.425-.3-.737T6 4t-.712.288T5 5v2H3V5q0-1.25.875-2.125T6 2h13.9L21 22zm2.6-2h2.325l-.475-7.6zm7.4-2h1.5v-4q.65-.15 1.075-.687T16 12.075V8h-1v3.775h-.75V8h-1v3.775h-.75V8h-1v4.075q0 .7.425 1.238T13 14z");
}

</style>
