<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5aywsbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5aywsbyj b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pie-chart-alt-2-filled" /></template>
