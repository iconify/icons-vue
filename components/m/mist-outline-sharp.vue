<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5eu3dbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mist-outline-sharp" /></template>
<style>
.t5eu3dbfv {
  fill: currentColor;
  d: path("M3 19v-2h12v2zm14 0v-2h4v2zM3 15v-2h4v2zm6 0v-2h12v2zm-6-4V9h13v2zm15 0V9h3v2zM3 7V5h7v2zm9 0V5h9v2z");
}

</style>
