<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga9bzj9gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ga9bzj9gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:x" /></template>
