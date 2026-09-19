<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r4eb564mb.css';
import '../../css/x/xw6vm1uka.css';
import '../../css/n/n2lvyflha.css';
import '../../css/x/xb8_cbr0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="r4eb564mb"/><path class="xw6vm1uka"/><circle transform="rotate(45 26.041 22.042)" class="n2lvyflha"/><path class="xb8_cbr0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:microscope-one" /></template>
