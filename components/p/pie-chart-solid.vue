<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2_r-ibel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j2_r-ibel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pie-chart-solid" /></template>
