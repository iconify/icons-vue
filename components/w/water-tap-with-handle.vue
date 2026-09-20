<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx3flsb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gx3flsb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-tap-with-handle" /></template>
