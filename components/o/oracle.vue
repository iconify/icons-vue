<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnzb1c__m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnzb1c__m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:oracle" /></template>
