<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e8i89z5nr.css';
import '../../css/s/sirrsrb_i.css';
import '../../css/z/zkyjh5bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e8i89z5nr"/><path class="sirrsrb_i"/><path class="zkyjh5bzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-off-linear" /></template>
