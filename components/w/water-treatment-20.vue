<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj4vzjb5q.css';
import '../../css/v/vnif4gbyf.css';
import '../../css/a/ads4cuuck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kj4vzjb5q"/><path class="vnif4gbyf"/><path class="ads4cuuck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-treatment-20" /></template>
