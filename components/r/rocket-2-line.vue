<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfq1-iboq.css';
import '../../css/x/x0ws1hdqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfq1-iboq"/><path class="x0ws1hdqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rocket-2-line" /></template>
