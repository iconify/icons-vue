<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0h_4qbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0h_4qbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-linear" /></template>
