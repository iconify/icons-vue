<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/z/zkcn4_12l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="zkcn4_12l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-solar-20" /></template>
