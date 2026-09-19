<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s61fxyb8s.css';
import '../../css/t/tyum8jbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s61fxyb8s"/><path class="tyum8jbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:svelte" /></template>
