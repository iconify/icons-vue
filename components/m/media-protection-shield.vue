<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dawrykb_t.css';
import '../../css/s/srztgmmzo.css';
import '../../css/u/ugkergbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dawrykb_t"/><path class="srztgmmzo"/><path class="ugkergbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:media-protection-shield" /></template>
