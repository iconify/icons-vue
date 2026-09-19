<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uejs2nbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uejs2nbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-resize" /></template>
