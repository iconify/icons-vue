<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0pd1zblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-selection-sharp" /></template>
<style>
.j0pd1zblm {
  fill: currentColor;
  d: path("M3 17v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4 12v-2h2v2zM7 5V3h2v2zm4 0V3h2v2zm1.5 16l-1.4-1.4l3.55-3.55l-3.55-3.55l1.4-1.4l3.55 3.55l3.55-3.55l1.4 1.4l-3.55 3.55L21 19.6L19.6 21l-3.55-3.55zM15 5V3h2v2zm4 4V7h2v2zM3 5V3h2v2zm18 0h-2V3h2zM3 21v-2h2v2z");
}

</style>
