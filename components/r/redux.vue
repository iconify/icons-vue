<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6dqfo8re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256,"top":-6};
const content = `<path class="d6dqfo8re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:redux" /></template>
