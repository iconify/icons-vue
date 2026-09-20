<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imwhrrb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imwhrrb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:run-line" /></template>
