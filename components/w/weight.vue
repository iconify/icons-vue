<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1v3__bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1v3__bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:weight" /></template>
