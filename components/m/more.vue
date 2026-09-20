<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d93mtf6nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d93mtf6nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:more" /></template>
