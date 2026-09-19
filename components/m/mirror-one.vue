<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b-396ydgx.css';
import '../../css/o/oa8odlbac.css';
import '../../css/t/tqvdlybjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="b-396ydgx"/><path class="oa8odlbac"/><path class="tqvdlybjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mirror-one" /></template>
