<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fft0npbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fft0npbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paw-print" /></template>
