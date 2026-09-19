<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htyf4ib6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="htyf4ib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:question-face" /></template>
