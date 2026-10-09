<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabfcuuto.css';
import '../../css/p/pg0nswt9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uabfcuuto"/><path class="pg0nswt9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ski-lift-20-bold" /></template>
