<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt02fdobb.css';
import '../../css/g/g0f4pkbnb.css';
import '../../css/p/p4vhzwb9g.css';
import '../../css/j/jmm_6pidh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt02fdobb"/><path class="g0f4pkbnb"/><path class="p4vhzwb9g"/><path class="jmm_6pidh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peanut" /></template>
