<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8-rrpbya.css';
import '../../css/z/z7_tv0bli.css';
import '../../css/j/ja3silbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c8-rrpbya"/><path class="z7_tv0bli"/><path class="ja3silbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nailpolish" /></template>
