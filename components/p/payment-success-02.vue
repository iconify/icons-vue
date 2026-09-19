<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zp0j2whzz.css';
import '../../css/i/icr3gcbor.css';
import '../../css/m/mkdq8fbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp0j2whzz"/><path class="icr3gcbor"/><path class="mkdq8fbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:payment-success-02" /></template>
