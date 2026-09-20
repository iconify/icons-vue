<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7v6wxb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w7v6wxb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfding-light" /></template>
