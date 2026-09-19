<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3hqbzbrl.css';
import '../../css/g/ge50lacpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b3hqbzbrl"/><path class="ge50lacpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-stroke-16" /></template>
