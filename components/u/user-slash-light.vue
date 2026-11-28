<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heiy4rbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="heiy4rbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-slash-light" /></template>
