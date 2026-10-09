<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb1scqbmo.css';
import '../../css/a/aqncqbc6o.css';
import '../../css/i/iomwkbcdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hb1scqbmo"/><path class="aqncqbc6o"/><path class="iomwkbcdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transformer-20" /></template>
