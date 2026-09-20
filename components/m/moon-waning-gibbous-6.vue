<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g53dd3b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="g53dd3b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waning-gibbous-6" /></template>
