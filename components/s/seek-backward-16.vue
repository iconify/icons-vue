<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_yzbdcai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_yzbdcai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:seek-backward-16" /></template>
