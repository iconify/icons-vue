<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iexxgd58y.css';
import '../../css/x/x8r3bo3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iexxgd58y"/><path class="x8r3bo3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:microservices-1" /></template>
