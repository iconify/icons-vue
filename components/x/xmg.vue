<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l45a9sbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l45a9sbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xmg" /></template>
