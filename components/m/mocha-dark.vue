<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hynasbbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1084};
const content = `<path class="hynasbbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mocha-dark" /></template>
