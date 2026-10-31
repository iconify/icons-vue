<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad6t1ls9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad6t1ls9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-fill-round" /></template>
