<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fut-rcs0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fut-rcs0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tower-cell" /></template>
