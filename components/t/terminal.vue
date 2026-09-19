<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u46mg0b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u46mg0b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:terminal" /></template>
