<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9opnqcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw9opnqcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:monitor-refresh" /></template>
