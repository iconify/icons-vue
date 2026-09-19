<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bepd9obom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bepd9obom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:personal-training" /></template>
