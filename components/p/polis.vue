<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggp6kzb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggp6kzb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:polis" /></template>
