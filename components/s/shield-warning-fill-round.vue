<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9q1o4bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9q1o4bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-fill-round" /></template>
