<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/b32gsdbth.css';
import '../../css/i/iwqeqib9j.css';
import '../../css/n/neojpkb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="b32gsdbth"/><path class="iwqeqib9j"/><path class="neojpkb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:play-cycle" /></template>
