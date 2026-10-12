<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4e8n_k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h4e8n_k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pencil-sparkle-fill-20" /></template>
