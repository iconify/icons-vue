<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soy094b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="soy094b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xmo" /></template>
