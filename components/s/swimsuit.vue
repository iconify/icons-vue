<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/h7tcblg-d.css';
import '../../css/o/og_licezb.css';
import '../../css/i/iavxncbnw.css';
import '../../css/j/j3l3upm6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="h7tcblg-d"/><circle class="og_licezb"/><circle class="iavxncbnw"/><path class="j3l3upm6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:swimsuit" /></template>
