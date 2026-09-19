<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylkih6j-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":430,"height":512};
const content = `<path class="ylkih6j-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:npm" /></template>
