<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/belo7nbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="belo7nbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-down-line" /></template>
