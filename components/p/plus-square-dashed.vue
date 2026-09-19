<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivqa_53qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivqa_53qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:plus-square-dashed" /></template>
