<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtk2x-umn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mtk2x-umn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume" /></template>
