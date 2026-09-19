<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw9-g6b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cw9-g6b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pivx" /></template>
