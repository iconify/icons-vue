<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istk9mqfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="istk9mqfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:video-play" /></template>
