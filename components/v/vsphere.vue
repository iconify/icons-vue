<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyun3gb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xyun3gb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vsphere" /></template>
