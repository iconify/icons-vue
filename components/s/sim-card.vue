<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxmj7wz7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fxmj7wz7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sim-card" /></template>
