<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6jl_bkj.css';
import '../../css/g/gb7t1obix.css';
import '../../css/c/ca-lc-jmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ly6jl_bkj"><path class="gb7t1obix"/><path class="ca-lc-jmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:ulikecam" /></template>
