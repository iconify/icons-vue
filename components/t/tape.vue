<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/tllbsg4up.css';
import '../../css/m/mail3acsf.css';
import '../../css/k/kcsygmb2d.css';
import '../../css/z/zxu45kbfa.css';
import '../../css/x/xdta9nrsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="tllbsg4up"/><path clip-rule="evenodd" class="mail3acsf"/><path class="kcsygmb2d"/><path class="zxu45kbfa"/><path class="xdta9nrsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:tape" /></template>
