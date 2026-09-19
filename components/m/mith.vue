<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md6qihbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="md6qihbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mith" /></template>
