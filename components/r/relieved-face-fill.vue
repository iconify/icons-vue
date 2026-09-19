<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i37p3-q5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i37p3-q5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:relieved-face-fill" /></template>
