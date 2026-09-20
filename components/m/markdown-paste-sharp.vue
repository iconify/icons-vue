<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wygbw7b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markdown-paste-sharp" /></template>
<style>
.wygbw7b-c {
  fill: currentColor;
  d: path("M12 21v-9h10v9h-2v-7h-2v5h-2v-5h-2v7zm-9 0V3h6.175q.275-.875 1.075-1.437T12 1q1 0 1.788.563T14.85 3H21v7h-2V5h-2v3H7V5H5v14h5v2zm9.713-16.288Q13 4.425 13 4t-.288-.712T12 3t-.712.288T11 4t.288.713T12 5t.713-.288");
}

</style>
