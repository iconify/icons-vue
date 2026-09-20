<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iopi0eb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iopi0eb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:surfshark" /></template>
