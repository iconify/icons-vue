<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b167aabvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b167aabvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-4-line" /></template>
