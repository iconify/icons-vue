<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/ozgrq5b1r.css';
import '../../css/l/l7avsacre.css';
import '../../css/q/qfez7pbdx.css';
import '../../css/b/bbx74dvkh.css';
import '../../css/f/f08pkdblx.css';
import '../../css/v/vdhgeqfxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="ozgrq5b1r"/><circle class="l7avsacre"/><circle class="qfez7pbdx"/><circle class="bbx74dvkh"/><path class="f08pkdblx"/><path class="vdhgeqfxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:whole-site-accelerator" /></template>
