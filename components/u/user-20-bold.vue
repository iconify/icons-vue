<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn-vy1b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pn-vy1b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-20-bold" /></template>
