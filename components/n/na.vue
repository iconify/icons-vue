<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/m/mx8eji3nw.css';
import '../../css/n/n9k6h4bor.css';
import '../../css/m/mm0l5c72t.css';
import '../../css/o/oomhlhgiw.css';
import '../../css/k/k8qpylxcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="mx8eji3nw"/><path class="n9k6h4bor"/><path class="mm0l5c72t"/><path class="oomhlhgiw"/><path class="k8qpylxcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:na" /></template>
