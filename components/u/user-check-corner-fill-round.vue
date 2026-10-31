<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl1vi9b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl1vi9b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-check-corner-fill-round" /></template>
