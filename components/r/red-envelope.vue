<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/me_ua9s0y.css';
import '../../css/o/o1xiz1bxm.css';
import '../../css/l/l54so-d8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="me_ua9s0y"/><path class="o1xiz1bxm"/><path class="l54so-d8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:red-envelope" /></template>
