<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc3w0nb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc3w0nb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-circle-x" /></template>
