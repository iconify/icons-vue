<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2nu4occ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ex2nu4occ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mini-link" /></template>
