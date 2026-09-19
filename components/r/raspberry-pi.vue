<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du2py5bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":407,"height":512};
const content = `<path class="du2py5bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:raspberry-pi" /></template>
