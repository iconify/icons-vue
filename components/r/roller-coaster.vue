<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wcji70blh.css';
import '../../css/t/tqd6mgdgh.css';
import '../../css/s/s1dmbnt6f.css';
import '../../css/q/qmr92_81l.css';
import '../../css/g/gm1nl1b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wcji70blh"/><path class="tqd6mgdgh"/><path class="s1dmbnt6f"/><path class="qmr92_81l"/><path class="gm1nl1b2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:roller-coaster" /></template>
