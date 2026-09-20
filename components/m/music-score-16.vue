<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk75zkjgm.css';
import '../../css/s/so77q_bes.css';
import '../../css/y/ylah79bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lk75zkjgm"/><path clip-rule="evenodd" class="so77q_bes"/><path class="ylah79bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:music-score-16" /></template>
