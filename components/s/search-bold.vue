<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oynu7p7ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oynu7p7ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:search-bold" /></template>
