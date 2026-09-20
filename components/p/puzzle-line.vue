<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5m-_tbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5m-_tbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:puzzle-line" /></template>
