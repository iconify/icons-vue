<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zbh99ubxk.css';
import '../../css/j/jjar52fez.css';
import '../../css/k/kz1lj24gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zbh99ubxk"/><path class="jjar52fez"/><path class="kz1lj24gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-in-broken" /></template>
