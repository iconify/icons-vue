<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cntfi1b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cntfi1b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ruler-alt" /></template>
