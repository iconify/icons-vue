<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zufn6ep.css';
import '../../css/g/g3a36eczr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6zufn6ep"/><path class="g3a36eczr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-high-48-bold" /></template>
