<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbl-y_rlh.css';
import '../../css/x/xxl63pf9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mbl-y_rlh"/><path class="xxl63pf9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:translate" /></template>
