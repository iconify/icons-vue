<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dt4y0wldq.css';
import '../../css/w/w52sjdwjn.css';
import '../../css/u/ua2rz5bkn.css';
import '../../css/x/x_27_2b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dt4y0wldq"/><path class="w52sjdwjn"/><path class="ua2rz5bkn"/><path class="x_27_2b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sliders-outline" /></template>
