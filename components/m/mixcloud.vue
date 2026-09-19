<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6annib7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="k6annib7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:mixcloud" /></template>
