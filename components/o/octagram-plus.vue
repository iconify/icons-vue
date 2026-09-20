<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsvgvmb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsvgvmb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:octagram-plus" /></template>
