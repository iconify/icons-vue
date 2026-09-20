<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh6_xb39i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh6_xb39i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pie-chart-remix" /></template>
