<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov2igo9rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov2igo9rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star5" /></template>
