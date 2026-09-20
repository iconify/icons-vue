<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yie0qniiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yie0qniiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:mustache" /></template>
