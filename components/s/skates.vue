<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e6b2l1b0w.css';
import '../../css/j/jzj6tdhdx.css';
import '../../css/c/c_zwkzr4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e6b2l1b0w"/><path class="jzj6tdhdx"/><path class="c_zwkzr4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:skates" /></template>
