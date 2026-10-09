<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_l8cd96n.css';
import '../../css/y/yo_3w-v9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h_l8cd96n"/><path class="yo_3w-v9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-x-20-bold" /></template>
