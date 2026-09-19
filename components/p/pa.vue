<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/m/mhu9k5_pu.css';
import '../../css/e/e-ol1g8zb.css';
import '../../css/m/mtjya3hdf.css';
import '../../css/r/r-toaehia.css';
import '../../css/l/l98r4-bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="mhu9k5_pu"/><path class="e-ol1g8zb"/><path class="mtjya3hdf"/><path class="r-toaehia"/><path class="l98r4-bsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:pa" /></template>
