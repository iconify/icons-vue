<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltlzg8bzb.css';
import '../../css/f/fqe-2wb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ltlzg8bzb"/><path class="fqe-2wb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-low-20-bold" /></template>
