<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xucik59fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xucik59fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:repeat-arrow" /></template>
