<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/vo49iohgp.css';
import '../../css/f/fs7g1xd7m.css';
import '../../css/r/rjzlgztql.css';
import '../../css/j/jkte4-baj.css';
import '../../css/m/mgsl8xddo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="vo49iohgp"/><circle class="fs7g1xd7m"/><path class="rjzlgztql"/><path class="jkte4-baj"/><path class="mgsl8xddo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mf" /></template>
