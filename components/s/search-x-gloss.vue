<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc34w8bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc34w8bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-x-gloss" /></template>
