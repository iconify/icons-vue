<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v855hut.css';
import '../../css/y/y5mawg3ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="y5mawg3ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-geothermal-48" /></template>
