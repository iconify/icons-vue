<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i--swg0uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="i--swg0uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:phone-square" /></template>
