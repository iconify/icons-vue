<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfd2lvbyk.css';
import '../../css/q/qfxjj7d4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfd2lvbyk"/><path class="qfxjj7d4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-vinyl-record" /></template>
