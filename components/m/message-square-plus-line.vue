<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt4b9ac1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4b9ac1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-plus-line" /></template>
