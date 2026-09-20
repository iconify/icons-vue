<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5jpbbtfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j5jpbbtfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-and-chefs-knife-and-pot" /></template>
