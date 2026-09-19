<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r5bdwzbjs.css';
import '../../css/e/edfg9vbrl.css';
import '../../css/c/c047ylp0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="r5bdwzbjs"/><path class="edfg9vbrl"/><circle class="c047ylp0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:projector-two" /></template>
