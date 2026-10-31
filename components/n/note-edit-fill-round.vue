<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubfh4dbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubfh4dbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-fill-round" /></template>
