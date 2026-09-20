<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1jvchi8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="q1jvchi8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-5" /></template>
