<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-7g8hbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-7g8hbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:music-2-fill" /></template>
