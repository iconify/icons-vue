<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f08ikcb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f08ikcb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:strikethrough-solid" /></template>
