<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2072ym-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="y2072ym-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:wordpress-wordmark" /></template>
