<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/p/psxdx4bcl.css';
import '../../css/h/he--fc8qg.css';
import '../../css/b/bt89lfbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="psxdx4bcl"/><circle class="he--fc8qg"/><path class="bt89lfbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:videocamera" /></template>
