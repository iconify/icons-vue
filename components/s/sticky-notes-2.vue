<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/v/vw7yqhc0j.css';
import '../../css/m/miqvqdosu.css';
import '../../css/v/vkl7yebus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="vw7yqhc0j"/><path class="miqvqdosu"/><path class="vkl7yebus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:sticky-notes-2" /></template>
