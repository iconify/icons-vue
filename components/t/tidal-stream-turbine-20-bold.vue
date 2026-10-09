<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4rl_dmmq.css';
import '../../css/z/z1x0aebyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4rl_dmmq"/><path class="z1x0aebyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-stream-turbine-20-bold" /></template>
