<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cbr0shbpp.css';
import '../../css/t/tqi_khm-q.css';
import '../../css/i/ilxf184hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cbr0shbpp"/><path class="tqi_khm-q"/><path class="ilxf184hs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:punching-ball-01" /></template>
