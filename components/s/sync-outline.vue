<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wic4l3bna.css';
import '../../css/j/j2rwd5epq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wic4l3bna"/><path class="j2rwd5epq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:sync-outline" /></template>
