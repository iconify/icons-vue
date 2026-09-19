<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0b8l-bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k0b8l-bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:step-insert" /></template>
