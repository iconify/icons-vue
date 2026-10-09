<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpxwtybmx.css';
import '../../css/n/n9tjabbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpxwtybmx"/><path class="n9tjabbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tanker-truck-20-bold" /></template>
