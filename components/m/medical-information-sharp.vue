<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxx6g_vaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:medical-information-sharp" /></template>
<style>
.lxx6g_vaj {
  fill: currentColor;
  d: path("M7 18h2v-2h2v-2H9v-2H7v2H5v2h2zm6-3.5h6V13h-6zm0 3h4V16h-4zM2 22V7h7V2h6v5h7v15zm9-13h2V4h-2z");
}

</style>
