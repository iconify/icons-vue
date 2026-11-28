<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unlol4xwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unlol4xwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-pause" /></template>
