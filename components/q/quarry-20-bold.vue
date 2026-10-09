<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmfxzub1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qmfxzub1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:quarry-20-bold" /></template>
