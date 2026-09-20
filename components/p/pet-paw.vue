<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzg7-ybcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qzg7-ybcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pet-paw" /></template>
