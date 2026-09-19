<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jegd8ybqs.css';
import '../../css/h/hrxogvq4w.css';
import '../../css/h/hayvu4isb.css';
import '../../css/b/bwxghiblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jegd8ybqs"/><path class="hrxogvq4w"/><path class="hayvu4isb"/><path class="bwxghiblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:timeline" /></template>
