<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm0ynk4zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zm0ynk4zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:thumbs-down" /></template>
