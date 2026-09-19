<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mqh_-8j2q.css';
import '../../css/y/ybvr_gb5s.css';
import '../../css/k/k2mh5kpet.css';
import '../../css/f/fuc7djkee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="mqh_-8j2q"/><path class="ybvr_gb5s"/><circle class="k2mh5kpet"/><path class="fuc7djkee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:people-search-one" /></template>
