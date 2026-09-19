<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1v0uv84v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1v0uv84v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:map-alt" /></template>
