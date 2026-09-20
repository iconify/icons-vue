<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlqpicc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:r-mobiledata-outline" /></template>
<style>
.rlqpicc6x {
  fill: currentColor;
  d: path("M3 10V3h4.385q.69 0 1.153.463T9 4.615V5.85q0 .466-.37.886q-.368.42-.907.541L8.885 10H7.846l-1.15-2.65H4V10zm1-3.65h3.385q.269 0 .442-.173T8 5.735v-1.12q0-.269-.173-.442T7.385 4H4z");
}

</style>
