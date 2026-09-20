<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/falp0fzqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="falp0fzqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:table-column-delete" /></template>
