<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7dfpmfcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x7dfpmfcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nuxt" /></template>
