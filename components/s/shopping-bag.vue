<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/obk3gsbvw.css';
import '../../css/a/az5cakobb.css';
import '../../css/n/nvarbzb-o.css';
import '../../css/x/xaiz4xbmd.css';
import '../../css/e/eqne90b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="obk3gsbvw"/><path class="az5cakobb"/><circle class="nvarbzb-o"/><path class="xaiz4xbmd"/><circle class="eqne90b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:shopping-bag" /></template>
