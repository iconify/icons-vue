<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur7q7lb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ur7q7lb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:steam-symbol" /></template>
