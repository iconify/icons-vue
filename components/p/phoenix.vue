<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0sbubcuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a0sbubcuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:phoenix" /></template>
