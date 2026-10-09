<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa37jgblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xa37jgblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:swimming-20" /></template>
