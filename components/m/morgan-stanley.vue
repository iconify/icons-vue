<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4b7xbbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":90};
const content = `<path class="q4b7xbbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:morgan-stanley" /></template>
