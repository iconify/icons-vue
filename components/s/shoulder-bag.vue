<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/qplorzbzz.css';
import '../../css/f/f494clbor.css';
import '../../css/e/eiifqcw6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="qplorzbzz"/><path class="f494clbor"/><circle class="eiifqcw6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:shoulder-bag" /></template>
