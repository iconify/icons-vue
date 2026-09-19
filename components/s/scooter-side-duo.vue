<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ovk7kx_2z.css';
import '../../css/x/xyd21cchs.css';
import '../../css/w/w68qzko4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ovk7kx_2z"/><path class="xyd21cchs"/><path class="w68qzko4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scooter-side-duo" /></template>
