<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glo4leblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="glo4leblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:seaplane-above-water" /></template>
