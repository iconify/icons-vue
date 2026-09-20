<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2d25ybfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2d25ybfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkles-fill" /></template>
