<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jskr7fbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jskr7fbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:microscope" /></template>
