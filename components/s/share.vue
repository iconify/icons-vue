<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwuxz88lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="cwuxz88lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:share" /></template>
