<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8co3-b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f8co3-b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:power" /></template>
