<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwtag8-5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jwtag8-5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:temporal" /></template>
