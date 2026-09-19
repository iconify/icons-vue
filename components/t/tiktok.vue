<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpg56_zsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qpg56_zsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tiktok" /></template>
