<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6z9ar0tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o6z9ar0tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:travelperk-light" /></template>
