<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tptn74bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tptn74bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-under-key" /></template>
