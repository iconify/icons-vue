<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjq_h3bgy.css';
import '../../css/h/h2vk8bchf.css';
import '../../css/m/m88iatbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mjq_h3bgy"/><path class="h2vk8bchf"/><path class="m88iatbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-line-20-bold" /></template>
