<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi_j_db9s.css';
import '../../css/d/dhxs8ubvn.css';
import '../../css/z/zstpfjybv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oi_j_db9s"/><path class="dhxs8ubvn"/><path class="zstpfjybv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:timer-20" /></template>
