<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z46x2ab_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z46x2ab_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:toothbrush-sparkles" /></template>
