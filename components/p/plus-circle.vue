<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghczc3bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghczc3bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:plus-circle" /></template>
