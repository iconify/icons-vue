<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rah527wei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rah527wei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:opened-folder" /></template>
