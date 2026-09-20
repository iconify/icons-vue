<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_cmy1b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-alert-sharp" /></template>
<style>
.b_cmy1b4z {
  fill: currentColor;
  d: path("M12.713 16.713Q13 16.425 13 16t-.288-.712T12 15t-.712.288T11 16t.288.713T12 17t.713-.288M11 13h2V7h-2zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
