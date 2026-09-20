<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej1v3t0wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ej1v3t0wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-tap-with-droplet" /></template>
