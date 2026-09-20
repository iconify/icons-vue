<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbs8e4bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<path class="lbs8e4bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:miro-light" /></template>
