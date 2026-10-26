<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhybq6bxs.css';
import '../../css/n/n5ithpbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dhybq6bxs"/><path class="n5ithpbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:toml" /></template>
