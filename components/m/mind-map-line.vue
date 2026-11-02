<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eya_1n8bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eya_1n8bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mind-map-line" /></template>
