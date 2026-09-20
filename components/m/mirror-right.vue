<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1jl8t0yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1jl8t0yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror-right" /></template>
