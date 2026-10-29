<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st5z-kkqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="st5z-kkqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nx" /></template>
