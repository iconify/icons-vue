<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnek59blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fnek59blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:salt" /></template>
