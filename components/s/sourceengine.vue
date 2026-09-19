<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izdfergmo.css';
import '../../css/v/vwvszy4rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="izdfergmo"/><path class="vwvszy4rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sourceengine" /></template>
