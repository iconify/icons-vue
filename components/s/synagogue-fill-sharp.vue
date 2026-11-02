<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqlnj5boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-fill-sharp" /></template>
<style>
.eqlnj5boq {
  fill: currentColor;
  d: path("M3 8c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 8v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm12.464 5l.866-1.5a.998.998 0 0 0-.866-1.5h-1.732l-.866-1.5a1.002 1.002 0 0 0-1.732 0l-.866 1.5H8.536a1.002 1.002 0 0 0-.866 1.5l.866 1.5l-.866 1.5a.998.998 0 0 0 .866 1.5h1.732l.866 1.5a1.002 1.002 0 0 0 1.732 0l.866-1.5h1.732a1.002 1.002 0 0 0 .866-1.5Z");
}

</style>
