<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/ot2ojyb-b.css';
import '../../css/b/bk8ioe9xt.css';
import '../../css/s/soka6eb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ot2ojyb-b"/><circle class="bk8ioe9xt"/><path class="soka6eb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:passport" /></template>
