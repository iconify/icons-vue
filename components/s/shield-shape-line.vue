<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvyx8shbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvyx8shbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shield-shape-line" /></template>
