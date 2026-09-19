<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi5f0rxnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fi5f0rxnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:notesdate" /></template>
