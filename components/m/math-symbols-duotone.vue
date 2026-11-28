<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cib79wb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cib79wb5b primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:math-symbols-duotone" /></template>
