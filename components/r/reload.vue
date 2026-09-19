<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dsdw4zbiz.css';
import '../../css/k/k4ub4p2ey.css';
import '../../css/b/bzxe9qa1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsdw4zbiz"/><path class="k4ub4p2ey"/><path class="bzxe9qa1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:reload" /></template>
