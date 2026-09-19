<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iic6xwb_c.css';
import '../../css/f/fq367fial.css';
import '../../css/i/iom_occzf.css';
import '../../css/w/wn7r_htmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="iic6xwb_c"/><path class="fq367fial"/><path class="iom_occzf"/><path class="wn7r_htmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:school-bus-outline" /></template>
