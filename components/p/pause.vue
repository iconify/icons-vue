<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glfie7b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="glfie7b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:pause" /></template>
