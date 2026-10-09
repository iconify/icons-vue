<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie3v5gb6w.css';
import '../../css/k/k4oej8buw.css';
import '../../css/h/h1qcumj4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ie3v5gb6w"/><path class="k4oej8buw"/><path class="h1qcumj4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whisk-20" /></template>
