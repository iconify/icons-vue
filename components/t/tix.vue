<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1yq4quw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dt1yq4quw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tix" /></template>
