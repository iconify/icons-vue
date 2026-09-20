<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szgh9cbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="szgh9cbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:smartphone-16" /></template>
