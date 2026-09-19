<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_pl-mkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="we_pl-mkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:n8n" /></template>
