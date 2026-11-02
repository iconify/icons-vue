<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd--d5ahu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd--d5ahu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steering-wheel-fill" /></template>
