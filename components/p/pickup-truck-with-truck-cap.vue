<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbgb-vbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qbgb-vbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-with-truck-cap" /></template>
