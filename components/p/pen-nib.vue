<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5-vgbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tb5-vgbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pen-nib" /></template>
