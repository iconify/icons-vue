<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3zgshbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3zgshbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:record-circle-line" /></template>
