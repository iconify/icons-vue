<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s32cdob1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s32cdob1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-fill-round" /></template>
