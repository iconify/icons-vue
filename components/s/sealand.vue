<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/p/p2a38cbao.css';
import '../../css/i/irx8lebrd.css';
import '../../css/d/dzzxmxfbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="p2a38cbao"/><path class="irx8lebrd"/><path class="dzzxmxfbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:sealand" /></template>
