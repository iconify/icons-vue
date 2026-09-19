<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bnpt7bcpa.css';
import '../../css/l/lg_3hrbjz.css';
import '../../css/h/hbtezcj3h.css';
import '../../css/q/qvzqv0bxn.css';
import '../../css/e/eg7jz2bwt.css';
import '../../css/o/o32m7o_mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bnpt7bcpa"/><path class="lg_3hrbjz"/><path class="hbtezcj3h"/><path class="qvzqv0bxn"/><path class="eg7jz2bwt"/><path class="o32m7o_mq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pivot-table" /></template>
