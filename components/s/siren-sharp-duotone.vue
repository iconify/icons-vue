<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/ikxifqblw.css';
import '../../css/z/zusgepdhq.css';
import '../../css/e/e5xtnl27s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ikxifqblw"/><path clip-rule="evenodd" class="zusgepdhq"/><path class="e5xtnl27s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:siren-sharp-duotone" /></template>
