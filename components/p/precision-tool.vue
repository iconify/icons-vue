<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipzk-7b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipzk-7b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:precision-tool" /></template>
