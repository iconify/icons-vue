<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dihyg454b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dihyg454b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:searchapi" /></template>
