<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnw8_jbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-lock-landscape-sharp" /></template>
<style>
.dnw8_jbub {
  fill: currentColor;
  d: path("M1 19V5h22v14zm5-2h12V7H6zm3-1v-5h1v-1q0-.825.588-1.412T12 8t1.413.588T14 10v1h1v5zm2-5h2v-1q0-.425-.288-.712T12 9t-.712.288T11 10z");
}

</style>
