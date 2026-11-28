<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp566-geb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp566-geb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:utensils-check" /></template>
