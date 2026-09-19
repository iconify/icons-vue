<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho1-ppbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ho1-ppbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:tag" /></template>
