<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7xv-rpmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m7xv-rpmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:polygon-wordmark" /></template>
