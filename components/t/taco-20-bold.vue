<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euckcfb8p.css';
import '../../css/h/h3oyx7bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="euckcfb8p"/><path class="h3oyx7bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taco-20-bold" /></template>
