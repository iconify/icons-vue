<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo0wrgluc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo0wrgluc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:xml" /></template>
