<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcczw9bad.css';
import '../../css/u/u5k1hcfaz.css';
import '../../css/j/jp-5skmgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wcczw9bad"><path class="u5k1hcfaz"/><path class="jp-5skmgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stream-bold" /></template>
