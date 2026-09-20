<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye4bivxcv.css';
import '../../css/u/uq7ud8o0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye4bivxcv"/><path class="uq7ud8o0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:wifi" /></template>
