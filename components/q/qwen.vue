<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd4pa2b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pd4pa2b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qwen" /></template>
