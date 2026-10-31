<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdymc7ifa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdymc7ifa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-warning-round" /></template>
