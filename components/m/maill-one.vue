<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/c/cj5929ymx.css';
import '../../css/q/q6v48yblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="utf5_xbzs"/><path class="cj5929ymx"/><path class="q6v48yblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:maill-one" /></template>
