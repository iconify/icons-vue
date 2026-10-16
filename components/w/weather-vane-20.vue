<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwzdr3l_o.css';
import '../../css/d/drba2d7_i.css';
import '../../css/l/lxvj2gbfp.css';
import '../../css/m/mqankgyhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwzdr3l_o"/><path class="drba2d7_i"/><path class="lxvj2gbfp"/><path class="mqankgyhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weather-vane-20" /></template>
