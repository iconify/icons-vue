<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfghmdbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfghmdbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:report-line-variant" /></template>
