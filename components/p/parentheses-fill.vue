<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyajv3zio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyajv3zio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parentheses-fill" /></template>
