<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pvq2a3bnf.css';
import '../../css/x/x39lujbyx.css';
import '../../css/c/c6upwkbge.css';
import '../../css/c/ceqt8o39a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pvq2a3bnf"/><path class="x39lujbyx"/><path class="c6upwkbge"/><path class="ceqt8o39a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-text-sparkles-sharp-duotone" /></template>
