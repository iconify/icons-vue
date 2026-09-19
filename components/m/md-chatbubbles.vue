<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnhy8pd4d.css';
import '../../css/s/srze-hcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nnhy8pd4d"/><path class="srze-hcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-chatbubbles" /></template>
