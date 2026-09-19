<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pao9cab5l.css';
import '../../css/n/nbo5_vccv.css';
import '../../css/r/rhfhlozer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pao9cab5l"/><path class="nbo5_vccv"/><path class="rhfhlozer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:refresh-double" /></template>
