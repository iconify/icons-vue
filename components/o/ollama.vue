<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu-l2rb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iu-l2rb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ollama" /></template>
