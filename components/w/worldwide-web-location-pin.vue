<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b2_rnpc_j.css';
import '../../css/b/br0jhivlx.css';
import '../../css/f/frdsqmb_e.css';
import '../../css/k/khkmn4rbj.css';
import '../../css/y/yp5hozbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b2_rnpc_j"/><path class="br0jhivlx"/><path class="frdsqmb_e"/><path class="khkmn4rbj"/><path class="yp5hozbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:worldwide-web-location-pin" /></template>
