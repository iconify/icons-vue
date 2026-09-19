<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u6sf2yaha.css';
import '../../css/n/n2uwyqbsw.css';
import '../../css/i/ie281-b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u6sf2yaha"/><path class="n2uwyqbsw"/><path class="ie281-b7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stroke-center" /></template>
