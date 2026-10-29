<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1104x9dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1104x9dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mountain-snow-solid" /></template>
