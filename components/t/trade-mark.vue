<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu6bp5bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="hu6bp5bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:trade-mark" /></template>
