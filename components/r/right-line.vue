<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiuuz9pso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiuuz9pso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:right-line" /></template>
