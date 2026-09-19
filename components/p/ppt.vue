<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r9ztc99mw.css';
import '../../css/z/zw37bnb8x.css';
import '../../css/m/m4vuqabns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="r9ztc99mw"/><path clip-rule="evenodd" class="zw37bnb8x"/><path class="m4vuqabns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:ppt" /></template>
