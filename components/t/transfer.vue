<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pxs1s4oab.css';
import '../../css/o/oes74zpfc.css';
import '../../css/m/mi9qcgc5h.css';
import '../../css/r/rk-rw9bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="pxs1s4oab"/><path class="oes74zpfc"/><circle class="mi9qcgc5h"/><circle class="rk-rw9bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:transfer" /></template>
