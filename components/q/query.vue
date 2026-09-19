<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs49pub-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xs49pub-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:query" /></template>
