<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f22wqelib.css';
import '../../css/l/l7q0ip_gf.css';
import '../../css/r/rx9asmbnf.css';
import '../../css/z/z5ec-kbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="f22wqelib"/><path class="l7q0ip_gf"/><path class="rx9asmbnf"/><path class="z5ec-kbwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:modify-two" /></template>
