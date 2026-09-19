<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xm80o4b2a.css';
import '../../css/d/d_0depbqg.css';
import '../../css/d/dx_hcswmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xm80o4b2a"/><circle class="d_0depbqg"/><path class="dx_hcswmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:watch-one" /></template>
