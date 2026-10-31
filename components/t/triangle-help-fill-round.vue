<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs4nm6bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4nm6bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-help-fill-round" /></template>
