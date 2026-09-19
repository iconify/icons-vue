<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0-o8vb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0-o8vb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:musical-note-sharp" /></template>
