<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv0y7fdcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":98,"height":29};
const content = `<path class="pv0y7fdcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pylon" /></template>
