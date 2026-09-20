<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-o3w7b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-o3w7b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:warning-o" /></template>
