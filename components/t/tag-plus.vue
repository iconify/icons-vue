<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4xyy74qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4xyy74qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tag-plus" /></template>
