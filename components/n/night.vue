<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ipgt47_0k.css';
import '../../css/r/r-pqkabzn.css';
import '../../css/f/f2_lv5bmr.css';
import '../../css/d/d6k18obis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ipgt47_0k"/><path class="r-pqkabzn"/><path clip-rule="evenodd" class="f2_lv5bmr"/><path class="d6k18obis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:night" /></template>
