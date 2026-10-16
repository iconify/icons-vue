<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2eib-bha.css';
import '../../css/g/gsrfvdbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o2eib-bha"/><path class="gsrfvdbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-high-20-bold" /></template>
