<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0qkuvese.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="r0qkuvese"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:projection-screen" /></template>
