<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rwhacnnbk.css';
import '../../css/g/geda3qblp.css';
import '../../css/f/fumudnnfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwhacnnbk"/><path class="geda3qblp"/><path class="fumudnnfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-pin-search" /></template>
