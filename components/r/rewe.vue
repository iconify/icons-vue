<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx1_1khoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx1_1khoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rewe" /></template>
