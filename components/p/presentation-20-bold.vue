<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_j6v7gna.css';
import '../../css/c/cbr70bcko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_j6v7gna"/><path class="cbr70bcko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:presentation-20-bold" /></template>
