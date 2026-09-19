<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/w/wj-7246uw.css';
import '../../css/j/jv08fcckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="wj-7246uw"/><path class="jv08fcckv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mt-civil-ensign" /></template>
