<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa_svdbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pa_svdbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:undo" /></template>
