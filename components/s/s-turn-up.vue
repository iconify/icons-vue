<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g995gab3y.css';
import '../../css/p/pkbervbtf.css';
import '../../css/k/kn1zr-vso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g995gab3y"/><path class="pkbervbtf"/><circle transform="rotate(-180 10 11)" class="kn1zr-vso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:s-turn-up" /></template>
