<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shfrclbgd.css';
import '../../css/q/q6p-x2blr.css';
import '../../css/o/okx76p-5g.css';
import '../../css/d/d9b0gub2o.css';
import '../../css/u/ug997tm-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="shfrclbgd"/><path clip-rule="evenodd" class="q6p-x2blr"/><path clip-rule="evenodd" class="okx76p-5g"/><path class="d9b0gub2o"/><path clip-rule="evenodd" class="ug997tm-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:qingniao-clue" /></template>
