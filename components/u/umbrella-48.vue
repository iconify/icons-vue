<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfommlbzh.css';
import '../../css/f/fhdrc_nuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfommlbzh"/><path class="fhdrc_nuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:umbrella-48" /></template>
