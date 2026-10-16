<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/v/vxbks-bbg.css';
import '../../css/f/fdky2dfsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="vxbks-bbg"/><path class="fdky2dfsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-nuclear-20" /></template>
