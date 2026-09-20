<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz_zvrfmn.css';
import '../../css/u/uofvvkbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lz_zvrfmn"/><path class="uofvvkbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-microphone-off" /></template>
