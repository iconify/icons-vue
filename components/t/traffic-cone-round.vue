<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srfvgfj4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srfvgfj4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-cone-round" /></template>
