<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/psxdx4bcl.css';
import '../../css/q/q83xo3b_h.css';
import '../../css/s/s7b7bgbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="psxdx4bcl"/><circle class="q83xo3b_h"/><path class="s7b7bgbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:videocamera" /></template>
