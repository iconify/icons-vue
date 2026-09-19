<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvilx1q3c.css';
import '../../css/x/xuwun2u6v.css';
import '../../css/h/hzpbaixyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="xuwun2u6v"/><path class="hzpbaixyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:sort" /></template>
