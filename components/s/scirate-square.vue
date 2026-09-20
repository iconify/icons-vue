<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/titw2rw2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="titw2rw2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:scirate-square" /></template>
