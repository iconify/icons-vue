<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/muvtlrodu.css';
import '../../css/z/zjxs2ab_r.css';
import '../../css/v/v-sv08b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="muvtlrodu"/><rect transform="rotate(90 36.006 19.334)" class="zjxs2ab_r"/><rect transform="rotate(-180 36.006 29.852)" class="v-sv08b6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:switch-one" /></template>
