<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggiu84btg.css';
import '../../css/p/pf2d4z5hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ggiu84btg"/><path class="pf2d4z5hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-play" /></template>
