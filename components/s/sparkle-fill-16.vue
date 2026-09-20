<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p429vcckz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p429vcckz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sparkle-fill-16" /></template>
