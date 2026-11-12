<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdt8x3_lk.css';
import '../../css/y/yurfh5b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kdt8x3_lk"/><path class="yurfh5b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reitti-dark" /></template>
