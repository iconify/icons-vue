<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to5_hpm1w.css';
import '../../css/h/h3bp_99ap.css';
import '../../css/o/obovem3ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":340,"height":340};
const content = `<g class="to5_hpm1w"><path clip-rule="evenodd" class="h3bp_99ap"/><path class="obovem3ey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wakatime-light" /></template>
