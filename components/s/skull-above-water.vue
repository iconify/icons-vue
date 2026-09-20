<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-0318zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oc-0318zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull-above-water" /></template>
