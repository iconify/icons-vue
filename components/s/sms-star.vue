<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/ikibw8b0n.css';
import '../../css/h/hkp0csiud.css';
import '../../css/k/kvz_424cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikibw8b0n"/><path class="hkp0csiud"/><path class="kvz_424cx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sms-star" /></template>
