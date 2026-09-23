<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/l-f044bhm.css';
import '../../css/x/xqu6_yb3l.css';
import '../../css/p/phzlwbbpe.css';
import '../../css/s/sau7yld-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l-f044bhm"/><path class="xqu6_yb3l"/><path class="phzlwbbpe"/><path class="sau7yld-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-sparkles-sharp-duotone" /></template>
