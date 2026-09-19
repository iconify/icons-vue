<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geqzp7bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="geqzp7bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ok" /></template>
