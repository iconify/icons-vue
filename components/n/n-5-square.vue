<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pso4n1bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="pso4n1bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:n-5-square" /></template>
