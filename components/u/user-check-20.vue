<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh3h573jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kh3h573jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-check-20" /></template>
