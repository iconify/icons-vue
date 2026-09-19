<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye0wxlu9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ye0wxlu9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:minus" /></template>
