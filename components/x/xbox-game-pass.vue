<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi7c8xbbv.css';
import '../../css/j/j04y387jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi7c8xbbv"/><path class="j04y387jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbox-game-pass" /></template>
