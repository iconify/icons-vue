<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb46l2bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jb46l2bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nmr" /></template>
