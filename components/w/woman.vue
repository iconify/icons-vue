<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/p/p-96z3bpw.css';
import '../../css/j/jt4c39h5v.css';
import '../../css/u/u4turoboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="p-96z3bpw"/><path class="jt4c39h5v"/><path class="u4turoboe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:woman" /></template>
