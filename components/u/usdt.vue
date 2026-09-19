<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y359-tbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y359-tbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:usdt" /></template>
