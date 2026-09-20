<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt5aatsrh.css';
import '../../css/x/xsgq8ckwo.css';
import '../../css/f/fodrk9f3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt5aatsrh"/><path class="xsgq8ckwo"/><path class="fodrk9f3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:music-note-circle-block-1" /></template>
