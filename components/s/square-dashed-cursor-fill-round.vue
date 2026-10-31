<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_oa09bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_oa09bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-fill-round" /></template>
