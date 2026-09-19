<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5r42tyxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="p5r42tyxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:postgresql" /></template>
