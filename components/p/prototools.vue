<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml9_4kbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ml9_4kbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:prototools" /></template>
