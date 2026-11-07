<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlavk1bjm.css';
import '../../css/p/phap5z8zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xlavk1bjm"/><path class="phap5z8zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-outline" /></template>
