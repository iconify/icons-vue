<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol0neq8oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ol0neq8oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pharmacy" /></template>
