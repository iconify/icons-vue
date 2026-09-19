<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye9clxgzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ye9clxgzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sketch-wordmark" /></template>
