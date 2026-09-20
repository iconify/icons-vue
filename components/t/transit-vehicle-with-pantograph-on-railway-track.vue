<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-qneenjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e-qneenjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:transit-vehicle-with-pantograph-on-railway-track" /></template>
