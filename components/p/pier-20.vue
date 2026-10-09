<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgs6dobqh.css';
import '../../css/o/o1usrlbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rgs6dobqh"/><path class="o1usrlbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pier-20" /></template>
