<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rycd7vtkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rycd7vtkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-2-bold" /></template>
