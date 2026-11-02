<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzezrgr8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzezrgr8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ticket-line" /></template>
