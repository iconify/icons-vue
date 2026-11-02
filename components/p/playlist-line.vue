<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6wvgz04r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6wvgz04r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playlist-line" /></template>
