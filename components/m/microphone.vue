<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/acxaut9dg.css';
import '../../css/n/nwplrgbog.css';
import '../../css/a/ab9b2_byt.css';
import '../../css/v/vz7twc1ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="acxaut9dg"/><path class="nwplrgbog"/><path class="ab9b2_byt"/><path class="vz7twc1ep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:microphone" /></template>
