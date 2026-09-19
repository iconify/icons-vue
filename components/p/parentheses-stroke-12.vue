<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgt6dvbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fgt6dvbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:parentheses-stroke-12" /></template>
