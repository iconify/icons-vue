<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jduyn0-zh.css';
import '../../css/m/mkolcyb2z.css';
import '../../css/f/f81lr3bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="jduyn0-zh"/><circle class="mkolcyb2z"/><path class="f81lr3bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:radio" /></template>
