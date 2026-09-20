<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw8qyw07p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw8qyw07p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pie-chart-2-line" /></template>
