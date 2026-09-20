<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqu52_xpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu52_xpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-area-line" /></template>
