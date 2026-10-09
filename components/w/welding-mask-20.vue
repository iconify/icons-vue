<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_07w6bdi.css';
import '../../css/s/s2rg5k4vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y_07w6bdi"/><path class="s2rg5k4vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:welding-mask-20" /></template>
