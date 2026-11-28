<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi474ab9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi474ab9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mic" /></template>
