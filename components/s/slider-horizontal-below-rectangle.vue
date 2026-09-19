<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1_0dc9au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y1_0dc9au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:slider-horizontal-below-rectangle" /></template>
