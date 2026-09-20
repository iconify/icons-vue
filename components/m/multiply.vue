<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y14ex5bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y14ex5bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:multiply" /></template>
