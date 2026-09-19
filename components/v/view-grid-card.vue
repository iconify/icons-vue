<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/f/fsan3yarc.css';
import '../../css/l/l5tjo4bak.css';
import '../../css/x/xbrl61bjm.css';
import '../../css/e/ed8432ijo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><rect class="fsan3yarc"/><rect class="l5tjo4bak"/><rect class="xbrl61bjm"/><rect class="ed8432ijo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:view-grid-card" /></template>
