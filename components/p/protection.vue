<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kmql86b4y.css';
import '../../css/x/xx16e09lg.css';
import '../../css/u/urcvvqb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kmql86b4y"/><path class="xx16e09lg"/><path class="urcvvqb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:protection" /></template>
