<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohlarcbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohlarcbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:threads-line" /></template>
