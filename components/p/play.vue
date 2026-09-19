<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8te-0b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z8te-0b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:play" /></template>
