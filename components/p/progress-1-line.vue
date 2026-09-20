<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3rbbxb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3rbbxb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-1-line" /></template>
