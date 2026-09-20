<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0on0uv4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-outline-sharp" /></template>
<style>
.t0on0uv4c {
  fill: currentColor;
  d: path("M12.713 5.713Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>
