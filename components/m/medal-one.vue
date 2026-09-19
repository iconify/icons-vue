<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/w-nbvvb-v.css';
import '../../css/n/ngnbouohf.css';
import '../../css/s/stxou8bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="w-nbvvb-v"/><circle class="ngnbouohf"/><circle class="stxou8bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:medal-one" /></template>
