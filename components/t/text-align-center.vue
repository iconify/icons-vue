<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3gahbc6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3gahbc6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:text-align-center" /></template>
