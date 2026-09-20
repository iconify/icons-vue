<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx5-28b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx5-28b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-2-line" /></template>
