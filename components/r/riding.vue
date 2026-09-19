<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bueyivd2g.css';
import '../../css/x/xcl2xpzvj.css';
import '../../css/s/ss_1d09nn.css';
import '../../css/q/q8ka45beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bueyivd2g"/><path class="xcl2xpzvj"/><circle class="ss_1d09nn"/><circle class="q8ka45beo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:riding" /></template>
