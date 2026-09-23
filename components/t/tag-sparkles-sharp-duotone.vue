<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/ml6y6ub5c.css';
import '../../css/q/q-x02trva.css';
import '../../css/h/hlvcfl71u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ml6y6ub5c"/><path class="q-x02trva"/><path class="hlvcfl71u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-sparkles-sharp-duotone" /></template>
