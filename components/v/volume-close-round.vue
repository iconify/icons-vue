<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw02nnoal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw02nnoal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-round" /></template>
