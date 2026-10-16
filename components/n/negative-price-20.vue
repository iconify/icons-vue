<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6og01bov.css';
import '../../css/r/riwyopb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6og01bov"/><path class="riwyopb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:negative-price-20" /></template>
