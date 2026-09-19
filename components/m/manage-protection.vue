<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey3vbs2kb.css';
import '../../css/m/mx54xpbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ey3vbs2kb"/><path class="mx54xpbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:manage-protection" /></template>
