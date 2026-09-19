<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/osjc_s7am.css';
import '../../css/l/l_1sesbbk.css';
import '../../css/s/seo7wx-_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="osjc_s7am"/><path class="l_1sesbbk"/><path class="seo7wx-_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radial" /></template>
