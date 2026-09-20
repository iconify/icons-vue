<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwfft0b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1084};
const content = `<path class="jwfft0b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mocha-light" /></template>
