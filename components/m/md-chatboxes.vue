<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2lktqd8u.css';
import '../../css/e/ejs_3u14j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2lktqd8u"/><path class="ejs_3u14j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-chatboxes" /></template>
