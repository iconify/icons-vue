<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh1f6ibkg.css';
import '../../css/a/ax8lognen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh1f6ibkg"/><path class="ax8lognen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yt-zero" /></template>
