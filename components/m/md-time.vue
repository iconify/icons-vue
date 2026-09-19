<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtylgdcmj.css';
import '../../css/w/wod7bgbrc.css';
import '../../css/t/tnokj8bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="jtylgdcmj"><path class="wod7bgbrc"/><path class="tnokj8bkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-time" /></template>
