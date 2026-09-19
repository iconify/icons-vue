<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/si64h9b3z.css';
import '../../css/d/d_7hulbhf.css';
import '../../css/a/a0_59cbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="si64h9b3z"/><path class="d_7hulbhf"/><path class="a0_59cbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:washing-machine" /></template>
