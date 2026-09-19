<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/c/cerazxb3v.css';
import '../../css/p/p7g9b60_x.css';
import '../../css/t/t19qk_bxn.css';
import '../../css/s/s6ecdhm2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="cerazxb3v"/><path class="p7g9b60_x"/><path class="t19qk_bxn"/><path class="s6ecdhm2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:sb" /></template>
