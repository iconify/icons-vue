<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/y3p5e-t4j.css';
import '../../css/m/ml1scxbze.css';
import '../../css/l/lo1lpdqfm.css';
import '../../css/s/sau7yld-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y3p5e-t4j"/><path class="ml1scxbze"/><path class="lo1lpdqfm"/><path class="sau7yld-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-sparkles-sharp-duotone" /></template>
