<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq3zkbbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq3zkbbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:presentation-line" /></template>
