<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thi0yobpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="thi0yobpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:sparkles" /></template>
