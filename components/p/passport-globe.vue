<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fch2tybje.css';
import '../../css/f/f3amrcc4b.css';
import '../../css/w/wnv2tkb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fch2tybje"/><path class="f3amrcc4b"/><path class="wnv2tkb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:passport-globe" /></template>
