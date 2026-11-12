<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf6dewbbb.css';
import '../../css/h/hwhw6hqjo.css';
import '../../css/y/yy5qrkvzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cf6dewbbb"/><path class="hwhw6hqjo"/><path class="yy5qrkvzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-terminal-light" /></template>
