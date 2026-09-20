<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2mk6acez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b2mk6acez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:phone-flat" /></template>
