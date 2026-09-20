<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt-fvkbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qt-fvkbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sobbing-face-in-circle" /></template>
