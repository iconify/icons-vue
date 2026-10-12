<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv6j1_b0y.css';
import '../../css/i/i2kxrqbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hv6j1_b0y"/><path class="i2kxrqbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mushroom-20-bold" /></template>
