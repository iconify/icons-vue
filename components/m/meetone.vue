<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftsci7nex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftsci7nex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:meetone" /></template>
