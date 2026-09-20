<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h33_-nbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h33_-nbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:researchgate" /></template>
