<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/milv0125p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="milv0125p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vite" /></template>
