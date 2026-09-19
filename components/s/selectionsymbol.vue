<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7qk6dbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="d7qk6dbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:selectionsymbol" /></template>
