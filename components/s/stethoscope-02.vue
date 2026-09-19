<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nr9qosbpk.css';
import '../../css/w/wxxouib_y.css';
import '../../css/k/kg1i0slxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nr9qosbpk"/><path class="wxxouib_y"/><path class="kg1i0slxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stethoscope-02" /></template>
