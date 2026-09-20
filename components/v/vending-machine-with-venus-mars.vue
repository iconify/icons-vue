<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpwog2bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dpwog2bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-venus-mars" /></template>
