<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-o4rlbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-o4rlbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-fill" /></template>
