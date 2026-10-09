<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joca-424g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="joca-424g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-medium-20-bold" /></template>
