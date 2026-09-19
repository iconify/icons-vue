<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/x/xdqh4gbub.css';
import '../../css/t/ta4flmb2c.css';
import '../../css/t/tl-og9bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="xdqh4gbub"/><path class="ta4flmb2c"/><circle class="tl-og9bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:stereo-one" /></template>
