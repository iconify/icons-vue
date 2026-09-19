<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/genx8sbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="genx8sbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pet-friendly" /></template>
