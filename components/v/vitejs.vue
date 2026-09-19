<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l05bfzngq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l05bfzngq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vitejs" /></template>
