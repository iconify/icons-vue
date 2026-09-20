<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6vm9d3lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c6vm9d3lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-valve-with-droplet" /></template>
