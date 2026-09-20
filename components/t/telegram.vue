<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gphxlac4x.css';
import '../../css/k/k5rc8zisb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gphxlac4x"/><path class="k5rc8zisb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:telegram" /></template>
