<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scpdkmq3k.css';
import '../../css/y/yst55_15i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="scpdkmq3k"/><path class="yst55_15i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:verilog" /></template>
