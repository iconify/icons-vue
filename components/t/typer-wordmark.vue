<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx_6q807q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yx_6q807q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typer-wordmark" /></template>
