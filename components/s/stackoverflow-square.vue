<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sga9agb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sga9agb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:stackoverflow-square" /></template>
