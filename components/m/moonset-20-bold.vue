<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8w6o6bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8w6o6bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moonset-20-bold" /></template>
