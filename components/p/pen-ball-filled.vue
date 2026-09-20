<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3xil-7-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3xil-7-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pen-ball-filled" /></template>
