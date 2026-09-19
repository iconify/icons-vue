<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0d0qdihh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="m0d0qdihh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:youtube" /></template>
