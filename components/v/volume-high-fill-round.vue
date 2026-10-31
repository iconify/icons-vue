<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlwfzf7fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlwfzf7fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-fill-round" /></template>
