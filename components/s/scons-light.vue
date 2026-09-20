<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9g4-upkk.css';
import '../../css/j/j4n-avbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i9g4-upkk"/><path class="j4n-avbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:scons-light" /></template>
