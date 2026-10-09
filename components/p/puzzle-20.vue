<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4_j55sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ov4_j55sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:puzzle-20" /></template>
