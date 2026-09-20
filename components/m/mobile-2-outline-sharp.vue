<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em3gdy5id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-2-outline-sharp" /></template>
<style>
.em3gdy5id {
  fill: currentColor;
  d: path("M12.713 19.713Q13 19.425 13 19t-.288-.712T12 18t-.712.288T11 19t.288.713T12 20t.713-.288M5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>
