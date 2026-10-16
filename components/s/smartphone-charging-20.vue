<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m417uzbhw.css';
import '../../css/l/l0mscrdyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m417uzbhw"/><path class="l0mscrdyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-charging-20" /></template>
