<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xds93kxwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-card-sharp" /></template>
<style>
.xds93kxwu {
  fill: currentColor;
  d: path("M11.385 21v-7.615H22V21zm1-1H21v-2.808h-8.615zm0-3.808H21v-1.807h-8.615zM9 19.392q-1.808-1.403-2.904-3.584T5 11.1V5.692l7-2.615l7 2.615V11H9z");
}

</style>
