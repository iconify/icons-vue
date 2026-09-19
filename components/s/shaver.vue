<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pqvkjslfz.css';
import '../../css/j/jjiany4ql.css';
import '../../css/q/qxq43kb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="pqvkjslfz"/><path class="jjiany4ql"/><path class="qxq43kb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:shaver" /></template>
