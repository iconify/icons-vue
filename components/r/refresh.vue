<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1np3qbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h1np3qbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:refresh" /></template>
