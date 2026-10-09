<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3lgxlbxk.css';
import '../../css/s/shu9gmbgv.css';
import '../../css/n/nbpoujbxo.css';
import '../../css/v/vsoe54eox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3lgxlbxk"/><path class="shu9gmbgv"/><path class="nbpoujbxo"/><path class="vsoe54eox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rooftop-wind-20-bold" /></template>
