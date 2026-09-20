<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwyqlacci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pwyqlacci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-bicycle" /></template>
