<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvba2ybat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvba2ybat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scan-line" /></template>
