<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/ao328ib6p.css';
import '../../css/d/dgn65lb1h.css';
import '../../css/t/tl_x59b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ao328ib6p"/><path class="dgn65lb1h"/><path class="tl_x59b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-01" /></template>
