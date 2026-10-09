<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyffe9boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tyffe9boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minus-20" /></template>
