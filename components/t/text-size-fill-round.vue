<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz-3uhbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-3uhbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-fill-round" /></template>
