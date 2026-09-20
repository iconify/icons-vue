<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew1qhpbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ew1qhpbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nodemon" /></template>
