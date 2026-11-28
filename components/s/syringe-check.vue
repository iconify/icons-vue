<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq1jeab-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq1jeab-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:syringe-check" /></template>
