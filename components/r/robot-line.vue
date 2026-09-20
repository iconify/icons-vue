<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w050vtbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w050vtbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:robot-line" /></template>
