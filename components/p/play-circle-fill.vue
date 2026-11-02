<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us89vp96s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us89vp96s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:play-circle-fill" /></template>
