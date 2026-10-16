<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py4unwgmu.css';
import '../../css/a/aqlii8bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":87.197};
const content = `<path class="py4unwgmu"/><path class="aqlii8bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nocobase-light" /></template>
