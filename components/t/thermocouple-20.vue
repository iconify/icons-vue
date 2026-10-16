<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwc8_0vln.css';
import '../../css/j/jwt9puapv.css';
import '../../css/h/hx1joebdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hwc8_0vln"/><path class="jwt9puapv"/><path class="hx1joebdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermocouple-20" /></template>
