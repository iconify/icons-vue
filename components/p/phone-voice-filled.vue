<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yimxbdbkz.css';
import '../../css/i/i-nbabcvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yimxbdbkz"/><path class="i-nbabcvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-voice-filled" /></template>
