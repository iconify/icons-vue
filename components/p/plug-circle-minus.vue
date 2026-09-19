<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh08mnboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hh08mnboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plug-circle-minus" /></template>
