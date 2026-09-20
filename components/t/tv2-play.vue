<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0knsgbev.css';
import '../../css/e/e9axqfb4f.css';
import '../../css/p/pdhn0vbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0knsgbev"/><path class="e9axqfb4f"/><path class="pdhn0vbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tv2-play" /></template>
