<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-lwpu35p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-lwpu35p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minimize-20" /></template>
