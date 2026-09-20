<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooyweo6zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:memory-sharp" /></template>
<style>
.ooyweo6zn {
  fill: currentColor;
  d: path("M9 15V9h6v6zm0 6v-2H5v-4H3v-2h2v-2H3V9h2V5h4V3h2v2h2V3h2v2h4v4h2v2h-2v2h2v2h-2v4h-4v2h-2v-2h-2v2zm8-4V7H7v10z");
}

</style>
