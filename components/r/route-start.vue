<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhhyhd2ni.css';
import '../../css/r/rug5b1b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yhhyhd2ni"/><path class="rug5b1b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:route-start" /></template>
