<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdz9c9buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdz9c9buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-pellets-20" /></template>
