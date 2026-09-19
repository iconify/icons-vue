<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhtp61rru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1792};
const content = `<path class="rhtp61rru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sun-o" /></template>
