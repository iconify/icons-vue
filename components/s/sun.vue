<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0z8wjhfw.css';
import '../../css/a/alnfi4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0z8wjhfw"/><path class="alnfi4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:sun" /></template>
