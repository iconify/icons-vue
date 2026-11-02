<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/latfltb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="latfltb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mars-stroke-line" /></template>
