<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q8dfmssmu.css';
import '../../css/s/s6ey6lbjj.css';
import '../../css/f/fduciibru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="q8dfmssmu"/><rect class="s6ey6lbjj"/><circle transform="matrix(0 -1 -1 0 30 24)" class="fduciibru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:wallet-three" /></template>
