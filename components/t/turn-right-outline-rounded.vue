<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj5s94btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-right-outline-rounded" /></template>
<style>
.yj5s94btc {
  fill: currentColor;
  d: path("M7 19v-8q0-.825.588-1.412T9 9h8.2l-.9-.9q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l2.6 2.6q.3.3.3.7t-.3.7l-2.6 2.6q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l.9-.9H9v8q0 .425-.288.713T8 20t-.712-.288T7 19");
}

</style>
