<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0hb7q3gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":405};
const content = `<path class="d0hb7q3gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xstate-dark" /></template>
