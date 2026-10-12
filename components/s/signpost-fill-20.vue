<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz7t-3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz7t-3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:signpost-fill-20" /></template>
