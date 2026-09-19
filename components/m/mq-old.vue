<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/n1hclzbdr.css';
import '../../css/q/qzb3rzbwv.css';
import '../../css/a/aoi7w1s0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="n1hclzbdr"/><path class="qzb3rzbwv"/><path class="aoi7w1s0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mq-old" /></template>
