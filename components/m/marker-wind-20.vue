<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/k/kue93s39j.css';
import '../../css/w/wop9ei26x.css';
import '../../css/w/ws7yeeb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="kue93s39j"/><path class="wop9ei26x"/><path class="ws7yeeb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-wind-20" /></template>
