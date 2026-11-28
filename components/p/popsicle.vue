<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia7a3j7zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia7a3j7zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:popsicle" /></template>
