<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1rj7u0mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y1rj7u0mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qwik" /></template>
