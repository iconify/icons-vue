<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukrge3umx.css';
import '../../css/y/ybpm01_ag.css';
import '../../css/z/zo-06kn-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukrge3umx"/><path class="ybpm01_ag"/><path class="zo-06kn-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-lock-20" /></template>
