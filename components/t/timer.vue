<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/kdt884bvj.css';
import '../../css/z/z7fxsb-bo.css';
import '../../css/l/l_4sj533p.css';
import '../../css/x/x7w7tncsi.css';
import '../../css/j/jq35rccjf.css';
import '../../css/a/a8v477jur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="kdt884bvj"/><path class="z7fxsb-bo"/><path class="l_4sj533p"/><path class="x7w7tncsi"/><path class="jq35rccjf"/><path class="a8v477jur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:timer" /></template>
