<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/numvsbbtg.css';
import '../../css/t/tbhcwf75b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="numvsbbtg"/><path class="tbhcwf75b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:seek-step" /></template>
