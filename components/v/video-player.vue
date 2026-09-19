<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytibtjceb.css';
import '../../css/z/zb00v0bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ytibtjceb"/><path class="zb00v0bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:video-player" /></template>
