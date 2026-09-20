<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz_npsbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mz_npsbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teleport" /></template>
