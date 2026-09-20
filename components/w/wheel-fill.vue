<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osvx2-h_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osvx2-h_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wheel-fill" /></template>
