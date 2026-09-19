<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk4mrjtlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jk4mrjtlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nodejs-wordmark" /></template>
