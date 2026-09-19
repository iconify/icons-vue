<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnee7sz0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hnee7sz0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opera" /></template>
