<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o500wtkuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o500wtkuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:toiletbrush" /></template>
