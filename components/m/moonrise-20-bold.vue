<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjml_t-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zjml_t-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moonrise-20-bold" /></template>
