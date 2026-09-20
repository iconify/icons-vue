<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y39xv8bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y39xv8bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-and-crescent-on-square" /></template>
