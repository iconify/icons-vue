<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgvk4cccp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgvk4cccp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-warning-fill-round" /></template>
