<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_wpfdbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w_wpfdbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nano-wordmark" /></template>
