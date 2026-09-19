<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/c/cs-7pkbny.css';
import '../../css/q/qu47k8blr.css';
import '../../css/g/g48e13jxo.css';
import '../../css/f/f-grrttlb.css';
import '../../css/e/edfxeussi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="cs-7pkbny"/><path class="qu47k8blr"/><path class="g48e13jxo"/><path class="f-grrttlb"/><path class="edfxeussi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:pt-20" /></template>
