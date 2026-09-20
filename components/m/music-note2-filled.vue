<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a423-p5qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a423-p5qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note2-filled" /></template>
