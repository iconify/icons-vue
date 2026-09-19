<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vwega_bod.css';
import '../../css/a/ahrbmubll.css';
import '../../css/k/kmxkex5-c.css';
import '../../css/m/mmd_h2bvz.css';
import '../../css/s/sp8biabka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vwega_bod"/><path class="ahrbmubll"/><path class="kmxkex5-c"/><path class="mmd_h2bvz"/><path class="sp8biabka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-sample" /></template>
