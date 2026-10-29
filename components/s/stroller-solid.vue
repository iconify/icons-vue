<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt151ebvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt151ebvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stroller-solid" /></template>
