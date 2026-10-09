<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbzbio0ay.css';
import '../../css/p/pbl0q7bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gbzbio0ay"/><path class="pbl0q7bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:palette-20-bold" /></template>
