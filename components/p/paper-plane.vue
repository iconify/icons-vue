<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cge0y-ejd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cge0y-ejd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:paper-plane" /></template>
