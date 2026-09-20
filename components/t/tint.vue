<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxvgkqbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hxvgkqbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tint" /></template>
