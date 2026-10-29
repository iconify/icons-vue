<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p222eqb9m.css';
import '../../css/n/n15o_72hl.css';
import '../../css/q/qvvp1bbua.css';
import '../../css/l/l28o8au4h.css';
import '../../css/v/v9fhfkb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p222eqb9m"/><path class="n15o_72hl wm-k"/><path class="qvvp1bbua wm-a"/><path class="l28o8au4h wm-k"/><path class="v9fhfkb7f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:umbrella-sketch" /></template>
