<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svgpb476e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svgpb476e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:percentage-fill" /></template>
