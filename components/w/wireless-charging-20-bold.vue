<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9abdnbmo.css';
import '../../css/q/q2o__te3v.css';
import '../../css/g/g4vsmpb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x9abdnbmo"/><path class="q2o__te3v"/><path class="g4vsmpb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wireless-charging-20-bold" /></template>
