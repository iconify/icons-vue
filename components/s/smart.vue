<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuarl10qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuarl10qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:smart" /></template>
