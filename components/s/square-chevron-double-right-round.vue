<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwntdc4ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwntdc4ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-right-round" /></template>
