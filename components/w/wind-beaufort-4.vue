<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlw2svjrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="tlw2svjrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-4" /></template>
