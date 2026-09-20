<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to-j83byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access" /></template>
<style>
.to-j83byk {
  fill: currentColor;
  d: path("M7 17V7h10v10zm-4 0v-2h2v2zm0-8V7h2v2zm4 12v-2h2v2zM7 5V3h2v2zm8 16v-2h2v2zm0-16V3h2v2zm4 12v-2h2v2zm0-8V7h2v2z");
}

</style>
