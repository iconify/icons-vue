<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tihaa0pcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tihaa0pcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-stack-3d-up-slash-fill" /></template>
