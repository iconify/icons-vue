<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yogscsb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yogscsb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:minus" /></template>
