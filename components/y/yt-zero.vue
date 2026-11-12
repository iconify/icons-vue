<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh1f6ibkg.css';
import '../../css/h/ht1gobb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh1f6ibkg"/><path class="ht1gobb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yt-zero" /></template>
