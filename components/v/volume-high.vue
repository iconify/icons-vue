<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkbae3hss.css';
import '../../css/k/ki89_nbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbae3hss"/><path class="ki89_nbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:volume-high" /></template>
