<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/k/kn2rl6b4x.css';
import '../../css/q/qgz7uvjgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="kn2rl6b4x"/><path class="qgz7uvjgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-battery-20" /></template>
