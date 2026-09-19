<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cz3f9ybru.css';
import '../../css/l/l-hmrlbkb.css';
import '../../css/j/j-s9jabwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cz3f9ybru"/><path class="l-hmrlbkb"/><path class="j-s9jabwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pot" /></template>
