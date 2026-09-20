<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3y6igytu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r3y6igytu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:superpowers" /></template>
