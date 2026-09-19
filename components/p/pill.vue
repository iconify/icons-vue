<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0m3i396l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0m3i396l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pill" /></template>
