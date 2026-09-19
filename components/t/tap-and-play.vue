<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ko1jb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":480};
const content = `<path class="o0ko1jb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tap-and-play" /></template>
