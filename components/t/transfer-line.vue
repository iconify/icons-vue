<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjxriqmdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjxriqmdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-line" /></template>
