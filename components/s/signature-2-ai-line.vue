<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv0ry_biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv0ry_biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-2-ai-line" /></template>
