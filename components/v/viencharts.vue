<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/m84lw8bft.css';
import '../../css/e/eq8_rgx0j.css';
import '../../css/f/fryp0s66n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="m84lw8bft"/><circle class="eq8_rgx0j"/><circle class="fryp0s66n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:viencharts" /></template>
