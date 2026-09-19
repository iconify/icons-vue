<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol3fxgb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol3fxgb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:stats-up" /></template>
