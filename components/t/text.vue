<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc-o3ybut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-o3ybut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:text" /></template>
