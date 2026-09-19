<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl-yfk1zi.css';
import '../../css/y/ydy8y_b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl-yfk1zi"/><path class="ydy8y_b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:webcam" /></template>
