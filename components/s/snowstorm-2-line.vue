<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7780pv2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7780pv2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-2-line" /></template>
