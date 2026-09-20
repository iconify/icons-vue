<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh0h06sep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vh0h06sep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:screwdriver" /></template>
