<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6r4aboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="oj6r4aboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:pubpeer-square" /></template>
