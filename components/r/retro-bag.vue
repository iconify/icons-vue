<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/midqvbcgl.css';
import '../../css/r/rmj10z9cb.css';
import '../../css/r/r47dkf1hc.css';
import '../../css/z/zd46sgbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="midqvbcgl"/><path class="rmj10z9cb"/><path class="r47dkf1hc"/><path class="zd46sgbja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:retro-bag" /></template>
