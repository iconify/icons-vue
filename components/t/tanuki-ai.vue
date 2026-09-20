<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbnvibyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bhbnvibyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:tanuki-ai" /></template>
