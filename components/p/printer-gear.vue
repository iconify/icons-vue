<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t218p1beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t218p1beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:printer-gear" /></template>
