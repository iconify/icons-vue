<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_c81byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_c81byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:view-grid-add" /></template>
