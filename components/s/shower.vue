<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0mn9fwnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0mn9fwnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shower" /></template>
