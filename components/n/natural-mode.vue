<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp24w_8tf.css';
import '../../css/f/f8cpqdg_j.css';
import '../../css/u/ux2lhde9c.css';
import '../../css/t/t-b_8j6mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="sp24w_8tf"><path class="f8cpqdg_j"/><path class="ux2lhde9c"/><path class="t-b_8j6mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:natural-mode" /></template>
