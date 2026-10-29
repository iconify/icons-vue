<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlk_m2tvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk_m2tvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-bottom" /></template>
