<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y__td5brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="y__td5brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-phone-flip" /></template>
