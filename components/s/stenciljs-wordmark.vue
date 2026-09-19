<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjthdubxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tjthdubxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:stenciljs-wordmark" /></template>
