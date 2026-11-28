<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2rku5b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2rku5b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parallelogram" /></template>
