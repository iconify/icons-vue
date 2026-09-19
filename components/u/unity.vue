<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmm9_6bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cmm9_6bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:unity" /></template>
