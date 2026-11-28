<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyw-02bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyw-02bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pie-chart-solid" /></template>
