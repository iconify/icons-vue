<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h74qk48ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h74qk48ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:share" /></template>
