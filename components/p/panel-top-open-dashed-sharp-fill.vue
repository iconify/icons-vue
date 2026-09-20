<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nz4nte95p.css';
import '../../css/j/jgv618mbj.css';
import '../../css/i/i4txdmb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nz4nte95p"/><path class="jgv618mbj"/><path class="i4txdmb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-open-dashed-sharp-fill" /></template>
