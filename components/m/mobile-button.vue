<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkd9v1vyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mkd9v1vyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mobile-button" /></template>
