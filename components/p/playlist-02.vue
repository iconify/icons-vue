<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u9-4m7han.css';
import '../../css/i/i54-r6grq.css';
import '../../css/z/z5ni2fbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u9-4m7han"/><path class="i54-r6grq"/><path class="z5ni2fbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:playlist-02" /></template>
