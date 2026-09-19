<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkuhdon-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nkuhdon-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:tauri" /></template>
