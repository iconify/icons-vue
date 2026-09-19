<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl6y03tsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yl6y03tsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:tumblr-square" /></template>
