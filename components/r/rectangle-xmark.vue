<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3yhi6rbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a3yhi6rbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:rectangle-xmark" /></template>
