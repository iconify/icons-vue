<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k52a32ocl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k52a32ocl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:percent-20-bold" /></template>
