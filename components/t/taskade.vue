<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffuyh2zgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ffuyh2zgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:taskade" /></template>
