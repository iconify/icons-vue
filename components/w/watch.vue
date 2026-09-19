<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g92amxlfl.css';
import '../../css/x/xnz_gs-_g.css';
import '../../css/j/jdh9hhorp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="g92amxlfl"/><path class="xnz_gs-_g"/><path class="jdh9hhorp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:watch" /></template>
