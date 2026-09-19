<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/wnwrmzb4d.css';
import '../../css/d/d52l-tb8w.css';
import '../../css/f/fbcpkibjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="wnwrmzb4d"/><path class="d52l-tb8w"/><path class="fbcpkibjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:prescription" /></template>
