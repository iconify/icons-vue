<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0h_hgbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-right-outline" /></template>
<style>
.k0h_hgbct {
  fill: currentColor;
  d: path("M7.48 19v-7.884q0-.672.473-1.144q.472-.472 1.143-.472h8.989l-2.1-2.1l.707-.708L20 10l-3.308 3.308l-.707-.708l2.1-2.1H9.096q-.269 0-.442.173t-.173.443V19z");
}

</style>
