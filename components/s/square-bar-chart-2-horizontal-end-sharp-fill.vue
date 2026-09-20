<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6_mn1fyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6_mn1fyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-2-horizontal-end-sharp-fill" /></template>
