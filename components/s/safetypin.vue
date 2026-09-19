<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggf-9fbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ggf-9fbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:safetypin" /></template>
