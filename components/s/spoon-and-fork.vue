<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyoprtbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hyoprtbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-and-fork" /></template>
