<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ghyioabfx.css';
import '../../css/k/kpco3xb7r.css';
import '../../css/t/t8y--cb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ghyioabfx"/><path clip-rule="evenodd" class="kpco3xb7r"/><path class="t8y--cb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:people-minus-one" /></template>
