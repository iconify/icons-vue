<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eri4cjb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eri4cjb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:skis" /></template>
