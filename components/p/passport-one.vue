<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/a83-n7b5d.css';
import '../../css/w/wi2d75bbx.css';
import '../../css/l/lnl1wm-up.css';
import '../../css/d/dgogtjsii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="a83-n7b5d"/><rect transform="rotate(-90 13 44)" class="wi2d75bbx"/><circle class="lnl1wm-up"/><path class="dgogtjsii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:passport-one" /></template>
