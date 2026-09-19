<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3wnob9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di3wnob9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:sort-outline" /></template>
