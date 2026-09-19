<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwmkq4b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hwmkq4b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mapbox" /></template>
