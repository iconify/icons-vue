<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiv_i_1yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv_i_1yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wind-turbine" /></template>
