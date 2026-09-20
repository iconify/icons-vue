<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5q0f_mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb5q0f_mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-off" /></template>
