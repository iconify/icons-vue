<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilpuybkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qilpuybkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:windows-outline" /></template>
