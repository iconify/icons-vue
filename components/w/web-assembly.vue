<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulra56alq.css';
import '../../css/b/bys5gtajl.css';
import '../../css/m/ms4qewg_b.css';
import '../../css/v/vdav4blva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="bys5gtajl"/><path class="ms4qewg_b"/><path class="vdav4blva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:web-assembly" /></template>
