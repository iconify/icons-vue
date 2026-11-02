<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti_d_mbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_d_mbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pickax-line" /></template>
