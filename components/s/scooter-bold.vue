<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzemr1byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzemr1byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scooter-bold" /></template>
