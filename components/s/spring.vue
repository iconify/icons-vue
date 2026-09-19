<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpuek5b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wpuek5b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spring" /></template>
