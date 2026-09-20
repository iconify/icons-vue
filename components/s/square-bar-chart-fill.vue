<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6ww8f0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fu6ww8f0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-fill" /></template>
