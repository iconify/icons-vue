<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8tkshbnt.css';
import '../../css/q/q1adlm-oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8tkshbnt"/><path class="q1adlm-oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:music-assistant" /></template>
