<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cap41rbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cap41rbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ngrok" /></template>
