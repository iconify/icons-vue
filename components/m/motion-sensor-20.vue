<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxmqlcbnm.css';
import '../../css/o/ot0n8509i.css';
import '../../css/v/vof4c6k-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fxmqlcbnm"/><path class="ot0n8509i"/><path class="vof4c6k-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motion-sensor-20" /></template>
