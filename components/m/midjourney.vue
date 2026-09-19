<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8p4k7b8x.css';
import '../../css/o/o2gadtdnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8p4k7b8x"/><path class="o2gadtdnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:midjourney" /></template>
