<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evr01px2z.css';
import '../../css/g/gousmcrku.css';
import '../../css/c/c9bx1tjcv.css';
import '../../css/w/wrvt_6b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="evr01px2z"/><path clip-rule="evenodd" class="gousmcrku"/><path class="c9bx1tjcv"/><path class="wrvt_6b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:tencent-qq" /></template>
