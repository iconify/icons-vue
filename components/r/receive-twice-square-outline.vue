<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfzrs9bdi.css';
import '../../css/d/d3al2xbaq.css';
import '../../css/y/yu1x-pnxh.css';
import '../../css/x/xu1xjobpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfzrs9bdi"/><path class="d3al2xbaq"/><path class="yu1x-pnxh"/><path clip-rule="evenodd" class="xu1xjobpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:receive-twice-square-outline" /></template>
