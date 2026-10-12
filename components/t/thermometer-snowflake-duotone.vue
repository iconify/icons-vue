<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zewt6pbzu.css';
import '../../css/m/m6mj_obaa.css';
import '../../css/p/pnmyt_1ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zewt6pbzu"/><path class="m6mj_obaa"/><path class="pnmyt_1ej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thermometer-snowflake-duotone" /></template>
