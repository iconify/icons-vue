<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfddwd_7g.css';
import '../../css/j/j0j3yqboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yfddwd_7g"/><path class="j0j3yqboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-settings" /></template>
