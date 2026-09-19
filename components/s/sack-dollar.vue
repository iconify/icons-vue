<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfmmmw5bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vfmmmw5bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sack-dollar" /></template>
