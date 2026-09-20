<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibcta7bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:on-hub-device-outline" /></template>
<style>
.ibcta7bcq {
  fill: currentColor;
  d: path("M8.923 19.77v-1h6.154v1zm0-2.77L8.038 5.689q-.055-.703.41-1.196Q8.914 4 9.616 4h4.769q.702 0 1.167.493t.41 1.195L15.077 17zm.927-1h4.3l.812-10.385q.019-.269-.145-.442T14.385 5h-4.77q-.269 0-.432.173q-.164.173-.144.443zm0-11h-.811h5.923z");
}

</style>
