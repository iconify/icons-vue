<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/x/xba517gct.css';
import '../../css/g/gkjh98waa.css';
import '../../css/x/xk4b4y77u.css';
import '../../css/m/m32fw5efl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="xba517gct"/><path class="gkjh98waa"/><circle class="xk4b4y77u"/><circle class="m32fw5efl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mk" /></template>
