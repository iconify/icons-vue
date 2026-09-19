<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5vrn7kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nv5vrn7kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tailwindcss" /></template>
