<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofvr46p3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofvr46p3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:scroll-text-line" /></template>
