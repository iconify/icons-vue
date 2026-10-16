<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o92oj3biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o92oj3biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ocean-acidification-20-bold" /></template>
