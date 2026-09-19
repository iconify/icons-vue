<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uj2u_c8xe.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/x/xln0-bxve.css';
import '../../css/h/hoffup77e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="uj2u_c8xe"/><g class="n1mjunbsu"><path class="xln0-bxve"/><path class="hoffup77e"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:pink" /></template>
