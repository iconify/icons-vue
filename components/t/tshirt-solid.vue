<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iznn3mbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iznn3mbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tshirt-solid" /></template>
