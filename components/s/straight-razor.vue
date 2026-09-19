<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r9wcz_ghl.css';
import '../../css/c/c2klbob3g.css';
import '../../css/h/hz9noobce.css';
import '../../css/q/q7yzux5pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect transform="rotate(-10 3.61 36.534)" class="r9wcz_ghl"/><path class="c2klbob3g"/><path class="hz9noobce"/><path class="q7yzux5pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:straight-razor" /></template>
