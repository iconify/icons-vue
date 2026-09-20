<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6o-j7b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-code-sharp" /></template>
<style>
.w6o-j7b9n {
  fill: currentColor;
  d: path("M5 23V1h14v5.1h1v4.8h-1V13H9v10zm9.6-.4L11 19l3.6-3.6l1.4 1.425L13.825 19L16 21.175zm4.8 0L18 21.175L20.175 19L18 16.825l1.4-1.425L23 19zM12.713 5.712Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288");
}

</style>
