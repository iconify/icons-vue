<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4-qyw_pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r4-qyw_pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish-under-water" /></template>
