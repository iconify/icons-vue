<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj5m3bbfz.css';
import '../../css/z/ziaiz_9lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tj5m3bbfz"/><path class="ziaiz_9lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-skip-back-outline" /></template>
