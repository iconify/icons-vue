<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mj39bccmk.css';
import '../../css/y/y8v-tql_s.css';
import '../../css/x/xw6xfpouc.css';
import '../../css/w/wxnxdnbfn.css';
import '../../css/s/sbvfr8zps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mj39bccmk"/><path class="y8v-tql_s"/><circle class="xw6xfpouc"/><path class="wxnxdnbfn"/><path class="sbvfr8zps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mounted" /></template>
