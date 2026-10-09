<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu6mrmzlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mu6mrmzlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sigma-20" /></template>
