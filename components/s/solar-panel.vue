<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma8_qib5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ma8_qib5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:solar-panel" /></template>
