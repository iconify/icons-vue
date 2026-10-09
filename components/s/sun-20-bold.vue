<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7s9a4brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l7s9a4brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-20-bold" /></template>
