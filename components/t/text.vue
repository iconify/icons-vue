<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/n/nrng1f7oh.css';
import '../../css/s/s1mp9v99t.css';
import '../../css/j/jmyzpn4cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="nrng1f7oh"/><path class="s1mp9v99t"/><path class="jmyzpn4cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:text" /></template>
