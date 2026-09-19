<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m8-2vl3ci.css';
import '../../css/k/kh86v1ben.css';
import '../../css/t/trc6hlbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8-2vl3ci"/><circle class="kh86v1ben"/><path class="trc6hlbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:robot-02" /></template>
