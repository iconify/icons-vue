<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yldvkm25s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yldvkm25s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-remove" /></template>
