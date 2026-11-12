<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/latfuii3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="latfuii3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:unraid-wordmark" /></template>
