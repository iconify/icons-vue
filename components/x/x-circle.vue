<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r62amn8ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r62amn8ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:x-circle" /></template>
