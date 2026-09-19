<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk57u1bly.css';
import '../../css/x/x2gu2vr4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk57u1bly"/><path class="x2gu2vr4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paint-roll" /></template>
