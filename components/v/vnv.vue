<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1e-7b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jo1e-7b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:vnv" /></template>
