<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqq9qe5dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqq9qe5dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-round" /></template>
