<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb2j65b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb2j65b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:world-line" /></template>
