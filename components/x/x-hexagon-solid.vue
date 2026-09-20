<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql0u9ebcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql0u9ebcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-hexagon-solid" /></template>
