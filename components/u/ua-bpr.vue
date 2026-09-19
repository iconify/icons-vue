<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/fu68vabvx.css';
import '../../css/a/a_b3olhpo.css';
import '../../css/m/m3q091brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="fu68vabvx"/><path class="a_b3olhpo"/><path class="m3q091brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:ua-bpr" /></template>
