<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycwaf5q0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ycwaf5q0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:systemd" /></template>
