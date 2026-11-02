<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdz--bb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdz--bb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-3-fill" /></template>
