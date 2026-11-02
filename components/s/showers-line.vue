<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6f6t4l1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6f6t4l1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:showers-line" /></template>
