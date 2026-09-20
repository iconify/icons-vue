<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-s21fbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-s21fbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:thumbsdown" /></template>
