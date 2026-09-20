<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz5b27bcw.css';
import '../../css/g/g205xvbso.css';
import '../../css/m/mqgqm8b7z.css';
import '../../css/n/ncstxp-xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2400,"height":2800};
const content = `<path class="rz5b27bcw"/><g class="g205xvbso"><path class="mqgqm8b7z"/><path class="ncstxp-xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:twitch" /></template>
