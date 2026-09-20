<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4wh8ccuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x4wh8ccuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-pole" /></template>
