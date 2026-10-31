<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkvfxxbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkvfxxbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-close-fill-round" /></template>
