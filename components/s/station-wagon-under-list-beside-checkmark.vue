<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv878y2jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv878y2jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-under-list-beside-checkmark" /></template>
