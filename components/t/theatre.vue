<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9lp3i2ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w9lp3i2ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:theatre" /></template>
