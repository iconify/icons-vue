<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyce9obdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyce9obdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:question-mark-circle-fill" /></template>
