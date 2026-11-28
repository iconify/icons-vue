<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt9l-mbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt9l-mbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:save-check" /></template>
