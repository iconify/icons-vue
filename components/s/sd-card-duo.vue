<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu_4_bcpi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bplvdbczi.css';
import '../../css/x/xtdwisb7h.css';
import '../../css/r/r3iq3lbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu_4_bcpi secondary"/><g class="dt0cm9dhy primary"><path class="bplvdbczi"/><path class="xtdwisb7h"/><path class="r3iq3lbmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sd-card-duo" /></template>
