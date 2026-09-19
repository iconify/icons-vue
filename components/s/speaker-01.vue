<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r1ddgfbve.css';
import '../../css/y/y2crqebri.css';
import '../../css/u/u0-5l2byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r1ddgfbve"/><circle class="y2crqebri"/><path class="u0-5l2byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:speaker-01" /></template>
