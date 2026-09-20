<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj7mkdbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj7mkdbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:notes" /></template>
