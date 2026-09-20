<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm7u26bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xm7u26bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-6" /></template>
