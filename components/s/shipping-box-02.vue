<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/od-h0hovn.css';
import '../../css/j/jr3d8_b8j.css';
import '../../css/m/m3t73ecme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="od-h0hovn"/><path class="jr3d8_b8j"/><path class="m3t73ecme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:shipping-box-02" /></template>
