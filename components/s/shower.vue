<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8n7vrbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8n7vrbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:shower" /></template>
