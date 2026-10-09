<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ogdpbce.css';
import '../../css/d/dhiwzmb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d9ogdpbce"/><path class="dhiwzmb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-20" /></template>
